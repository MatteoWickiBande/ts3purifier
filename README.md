## How to install

### Compiling

```
gcc -c -fPIC src/plugin.c -I include/ -o plugin.o
gcc plugin.o -shared -o libpurifier_plugin.so
```

### Installing

Just copy the .so file to your TS3 plugin folder. For example:
```
cp libpurifier_plugin.so /opt/teamspeak3/plugins/
```
