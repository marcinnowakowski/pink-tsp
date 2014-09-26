# pink-tsp - "Does pink suit traveling salesmen?"

```bash
git clone git://github.com/marcinnowakowski/pink-tsp.git
```

## How it was created?

```bash
### Create projects collection directory
mkdir pink_tsp
cd pink_tsp
vi README.md

### Install lein
wget https://raw.github.com/technomancy/leiningen/stable/bin/lein
sudo mv lein /usr/local/bin
sudo chmod +x /usr/local/bin/lein.

### Create a project
lein new app pink-tsp-engine
cd pink-tsp-engine
vi README.md
```

If you are into Ecplise
Install Eclipse i.e Luna 4.3.<br>
Install counterclockwise plugin (https://code.google.com/p/counterclockwise/)<br>
using update side (http://updatesite.ccw-ide.org/stable/).
```bash
### Adding IDE support as user level lein plugin
vi ../../.lein/profiles.clj
#>>
#{:user {:plugins [[lein-idefiles "0.2.1"]]}}
#<<
lein idefiles eclipse
```
File->Import...->General/Existing Project In Workspace

## Contributors

* Marcin Nowakowski

## License

Copyright © 2014 Marcin Nowakowski and contributors.

Distributed under the Eclipse Public License, the same as Clojure.
