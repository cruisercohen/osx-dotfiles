# osx-dotfiles
dotfiles (and other configuration) for my OSX systems

Most of these are in use.

etc/paths seems like it matches current default pretty way so may not be needed

Library/LaunchDaemons files address the maximum open files and processes limits that sometimes come up when running applications with lots of process and file requirements. I've seen it running large node apps or a large ecosystem of docker containers composed together as a deve environment. See links for more info

`launchctl limit to view limits`

* https://docs.basho.com/riak/kv/2.1.4/using/performance/open-files-limit/#mac-os-x
* https://gist.github.com/tombigel/d503800a282fcadbee14b537735d202c
* http://blog.ghostinthemachines.com/2010/01/19/mac-os-x-fork-resource-temporarily-unavailable/
