CMD vs ENTRYPOINT
==================
1. CMD instruction can be overriden
2. You can't override ENTRYPOINT --> ping google.com ping facebook.com. If you try to override entrypoint it will not override, but it will append
3. for best results we can use CMD and ENTRYPOINT together.
4. We can mention command in ENTRYPOINT, default options/inputs can be supplied through CMD. User can always override default options.
5. Only one CMD and one ENTRYPOINT should be used in Dockerfile
