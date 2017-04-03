# api documentation for  [dockerode (v2.4.3)](https://github.com/apocas/dockerode#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-dockerode.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-dockerode) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-dockerode.svg)](https://travis-ci.org/npmdoc/node-npmdoc-dockerode)
#### Docker Remote API module.

[![NPM](https://nodei.co/npm/dockerode.png?downloads=true)](https://www.npmjs.com/package/dockerode)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dockerode/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-dockerode_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dockerode/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-dockerode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-dockerode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pedro Dias",
        "email": "petermdias@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/apocas/dockerode/issues"
    },
    "contributors": [
        {
            "name": "Pedro Dias",
            "email": "petermdias@gmail.com",
            "url": "https://github.com/apocas"
        },
        {
            "name": "James Lal",
            "email": "jlal@mozilla.com",
            "url": "https://github.com/lightsofapollo"
        },
        {
            "name": "Ron Waldon",
            "email": "jokeyrhyme@gmail.com",
            "url": "https://github.com/jokeyrhyme"
        },
        {
            "name": "Everton Ribeiro",
            "email": "nuxlli@gmail.com",
            "url": "https://github.com/nuxlli"
        },
        {
            "name": "Sam Rijs",
            "email": "srijs@airpost.net",
            "url": "https://github.com/srijs"
        },
        {
            "name": "Shannon Poole",
            "email": "shannon.m.poole@gmail.com",
            "url": "https://github.com/shannonmpoole"
        },
        {
            "name": "Max Claus Nunes",
            "email": "maxcnunes@gmail.com",
            "url": "https://github.com/maxcnunes"
        },
        {
            "name": "Mike MacCana",
            "email": "mike.maccana@gmail.com",
            "url": "https://github.com/mikemaccana"
        },
        {
            "name": "Niclas Hoyer",
            "url": "https://github.com/niclashoyer"
        },
        {
            "name": "Nicholas Morsman",
            "email": "nicholas@publishlab.com",
            "url": "https://github.com/nmorsman"
        },
        {
            "name": "Philip Reichenberger",
            "url": "https://github.com/preichenberger"
        },
        {
            "name": "Anton Serdyuk",
            "email": "anton.serdyuk@gmail.com",
            "url": "https://github.com/m00t"
        },
        {
            "name": "Dan Williams",
            "email": "me+github@deedubs.com",
            "url": "https://github.com/deedubs"
        },
        {
            "name": "Alex Wolfe",
            "email": "alexkwolfe@gmail.com",
            "url": "https://github.com/alexkwolfe"
        },
        {
            "name": "Henry Allen-Tilford",
            "email": "htilford@gmail.com",
            "url": "https://github.com/generalhenry"
        },
        {
            "name": "Geoffrey Bachelet",
            "email": "geoffrey.bachelet@gmail.com",
            "url": "https://github.com/ubermuda"
        },
        {
            "name": "Jacob Friis Saxberg",
            "email": "jacob@saxberg.dk",
            "url": "https://github.com/webjay"
        },
        {
            "name": "Jeffrey Morgan",
            "email": "jmorganca@gmail.com",
            "url": "https://github.com/jeffdm"
        },
        {
            "name": "Kishore Nallan",
            "email": "kishore@kishorelive.com",
            "url": "https://github.com/kishorenc"
        },
        {
            "name": "Mathias Buus",
            "email": "mathiasbuus@gmail.com",
            "url": "https://github.com/mafintosh"
        },
        {
            "name": "Matthew Gallagher",
            "email": "mattva01@gmail.com",
            "url": "https://github.com/mattva01"
        },
        {
            "name": "Wojciech Kocjan",
            "url": "https://github.com/wojciechka"
        },
        {
            "name": "Mike Macaulay",
            "email": "mmacaula@gmail.com",
            "url": "https://github.com/mmacaula"
        },
        {
            "name": "Josh Matthews",
            "email": "josh@jmatthews.us",
            "url": "https://github.com/jmatth"
        },
        {
            "name": "Vincent Woo",
            "email": "vincent@coderpad.io",
            "url": "https://github.com/vincentwoo"
        },
        {
            "name": "Lewis J Ellis",
            "email": "me@lewisjellis.com",
            "url": "https://github.com/LewisJEllis"
        },
        {
            "name": "Adam Duncan",
            "url": "https://github.com/microadam"
        }
    ],
    "dependencies": {
        "concat-stream": "~1.5.1",
        "docker-modem": "0.3.x",
        "tar-fs": "~1.12.0"
    },
    "description": "Docker Remote API module.",
    "devDependencies": {
        "bluebird": "^3.5.0",
        "chai": "^3.5.0",
        "memorystream": "~0.2.0",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7ec55b492fc9f289e77325ff07c6a3a96021b4f2",
        "tarball": "https://registry.npmjs.org/dockerode/-/dockerode-2.4.3.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "gitHead": "7782d033f044acba2683e48e4068033095d21ba2",
    "homepage": "https://github.com/apocas/dockerode#readme",
    "keywords": [
        "docker",
        "docker.io"
    ],
    "license": "Apache-2.0",
    "main": "./lib/docker",
    "maintainers": [
        {
            "name": "apocas",
            "email": "petermdias@gmail.com"
        }
    ],
    "name": "dockerode",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/apocas/dockerode.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha -R spec"
    },
    "version": "2.4.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module dockerode](#apidoc.module.dockerode)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Container (modem, id)](#apidoc.element.dockerode.Container)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Exec (modem, id)](#apidoc.element.dockerode.Exec)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Image (modem, name)](#apidoc.element.dockerode.Image)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Network (modem, id)](#apidoc.element.dockerode.Network)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Node (modem, id)](#apidoc.element.dockerode.Node)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Plugin (modem, name, remote)](#apidoc.element.dockerode.Plugin)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Secret (modem, id)](#apidoc.element.dockerode.Secret)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Service (modem, id)](#apidoc.element.dockerode.Service)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Task (modem, id)](#apidoc.element.dockerode.Task)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Volume (modem, name)](#apidoc.element.dockerode.Volume)
1.  object <span class="apidocSignatureSpan">dockerode.</span>Container.prototype
1.  object <span class="apidocSignatureSpan">dockerode.</span>Exec.prototype
1.  object <span class="apidocSignatureSpan">dockerode.</span>Image.prototype
1.  object <span class="apidocSignatureSpan">dockerode.</span>Network.prototype
1.  object <span class="apidocSignatureSpan">dockerode.</span>Node.prototype
1.  object <span class="apidocSignatureSpan">dockerode.</span>Plugin.prototype
1.  object <span class="apidocSignatureSpan">dockerode.</span>Secret.prototype
1.  object <span class="apidocSignatureSpan">dockerode.</span>Service.prototype
1.  object <span class="apidocSignatureSpan">dockerode.</span>Task.prototype
1.  object <span class="apidocSignatureSpan">dockerode.</span>Volume.prototype
1.  object <span class="apidocSignatureSpan">dockerode.</span>util

#### [module dockerode.Container](#apidoc.module.dockerode.Container)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Container (modem, id)](#apidoc.element.dockerode.Container.Container)

#### [module dockerode.Container.prototype](#apidoc.module.dockerode.Container.prototype)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>attach (opts, callback)](#apidoc.element.dockerode.Container.prototype.attach)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>changes (callback)](#apidoc.element.dockerode.Container.prototype.changes)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>commit (opts, callback)](#apidoc.element.dockerode.Container.prototype.commit)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>copy (opts, callback)](#apidoc.element.dockerode.Container.prototype.copy)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>exec (opts, callback)](#apidoc.element.dockerode.Container.prototype.exec)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>export (callback)](#apidoc.element.dockerode.Container.prototype.export)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>getArchive (opts, callback)](#apidoc.element.dockerode.Container.prototype.getArchive)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>infoArchive (opts, callback)](#apidoc.element.dockerode.Container.prototype.infoArchive)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>inspect (opts, callback)](#apidoc.element.dockerode.Container.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>kill (opts, callback)](#apidoc.element.dockerode.Container.prototype.kill)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>logs (opts, callback)](#apidoc.element.dockerode.Container.prototype.logs)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>pause (opts, callback)](#apidoc.element.dockerode.Container.prototype.pause)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>putArchive (file, opts, callback)](#apidoc.element.dockerode.Container.prototype.putArchive)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>remove (opts, callback)](#apidoc.element.dockerode.Container.prototype.remove)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>rename (opts, callback)](#apidoc.element.dockerode.Container.prototype.rename)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>resize (opts, callback)](#apidoc.element.dockerode.Container.prototype.resize)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>restart (opts, callback)](#apidoc.element.dockerode.Container.prototype.restart)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>start (opts, callback)](#apidoc.element.dockerode.Container.prototype.start)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>stats (opts, callback)](#apidoc.element.dockerode.Container.prototype.stats)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>stop (opts, callback)](#apidoc.element.dockerode.Container.prototype.stop)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>top (opts, callback)](#apidoc.element.dockerode.Container.prototype.top)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>unpause (opts, callback)](#apidoc.element.dockerode.Container.prototype.unpause)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>update (opts, callback)](#apidoc.element.dockerode.Container.prototype.update)
1.  [function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>wait (callback)](#apidoc.element.dockerode.Container.prototype.wait)

#### [module dockerode.Exec](#apidoc.module.dockerode.Exec)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Exec (modem, id)](#apidoc.element.dockerode.Exec.Exec)

#### [module dockerode.Exec.prototype](#apidoc.module.dockerode.Exec.prototype)
1.  [function <span class="apidocSignatureSpan">dockerode.Exec.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Exec.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">dockerode.Exec.prototype.</span>resize (opts, callback)](#apidoc.element.dockerode.Exec.prototype.resize)
1.  [function <span class="apidocSignatureSpan">dockerode.Exec.prototype.</span>start (opts, callback)](#apidoc.element.dockerode.Exec.prototype.start)

#### [module dockerode.Image](#apidoc.module.dockerode.Image)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Image (modem, name)](#apidoc.element.dockerode.Image.Image)

#### [module dockerode.Image.prototype](#apidoc.module.dockerode.Image.prototype)
1.  [function <span class="apidocSignatureSpan">dockerode.Image.prototype.</span>get (callback)](#apidoc.element.dockerode.Image.prototype.get)
1.  [function <span class="apidocSignatureSpan">dockerode.Image.prototype.</span>history (callback)](#apidoc.element.dockerode.Image.prototype.history)
1.  [function <span class="apidocSignatureSpan">dockerode.Image.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Image.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">dockerode.Image.prototype.</span>push (opts, callback, auth)](#apidoc.element.dockerode.Image.prototype.push)
1.  [function <span class="apidocSignatureSpan">dockerode.Image.prototype.</span>remove (opts, callback)](#apidoc.element.dockerode.Image.prototype.remove)
1.  [function <span class="apidocSignatureSpan">dockerode.Image.prototype.</span>tag (opts, callback)](#apidoc.element.dockerode.Image.prototype.tag)

#### [module dockerode.Network](#apidoc.module.dockerode.Network)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Network (modem, id)](#apidoc.element.dockerode.Network.Network)

#### [module dockerode.Network.prototype](#apidoc.module.dockerode.Network.prototype)
1.  [function <span class="apidocSignatureSpan">dockerode.Network.prototype.</span>connect (opts, callback)](#apidoc.element.dockerode.Network.prototype.connect)
1.  [function <span class="apidocSignatureSpan">dockerode.Network.prototype.</span>disconnect (opts, callback)](#apidoc.element.dockerode.Network.prototype.disconnect)
1.  [function <span class="apidocSignatureSpan">dockerode.Network.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Network.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">dockerode.Network.prototype.</span>remove (opts, callback)](#apidoc.element.dockerode.Network.prototype.remove)

#### [module dockerode.Node](#apidoc.module.dockerode.Node)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Node (modem, id)](#apidoc.element.dockerode.Node.Node)

#### [module dockerode.Node.prototype](#apidoc.module.dockerode.Node.prototype)
1.  [function <span class="apidocSignatureSpan">dockerode.Node.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Node.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">dockerode.Node.prototype.</span>remove (callback)](#apidoc.element.dockerode.Node.prototype.remove)
1.  [function <span class="apidocSignatureSpan">dockerode.Node.prototype.</span>update (opts, callback)](#apidoc.element.dockerode.Node.prototype.update)

#### [module dockerode.Plugin](#apidoc.module.dockerode.Plugin)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Plugin (modem, name, remote)](#apidoc.element.dockerode.Plugin.Plugin)

#### [module dockerode.Plugin.prototype](#apidoc.module.dockerode.Plugin.prototype)
1.  [function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>configure (opts, callback)](#apidoc.element.dockerode.Plugin.prototype.configure)
1.  [function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>disable (opts, callback)](#apidoc.element.dockerode.Plugin.prototype.disable)
1.  [function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>enable (opts, callback)](#apidoc.element.dockerode.Plugin.prototype.enable)
1.  [function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Plugin.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>privileges (callback)](#apidoc.element.dockerode.Plugin.prototype.privileges)
1.  [function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>pull (opts, callback)](#apidoc.element.dockerode.Plugin.prototype.pull)
1.  [function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>push (opts, callback)](#apidoc.element.dockerode.Plugin.prototype.push)
1.  [function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>remove (opts, callback)](#apidoc.element.dockerode.Plugin.prototype.remove)
1.  [function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>upgrade (auth, opts, callback)](#apidoc.element.dockerode.Plugin.prototype.upgrade)

#### [module dockerode.Secret](#apidoc.module.dockerode.Secret)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Secret (modem, id)](#apidoc.element.dockerode.Secret.Secret)

#### [module dockerode.Secret.prototype](#apidoc.module.dockerode.Secret.prototype)
1.  [function <span class="apidocSignatureSpan">dockerode.Secret.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Secret.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">dockerode.Secret.prototype.</span>remove (opts, callback)](#apidoc.element.dockerode.Secret.prototype.remove)
1.  [function <span class="apidocSignatureSpan">dockerode.Secret.prototype.</span>update (opts, callback)](#apidoc.element.dockerode.Secret.prototype.update)

#### [module dockerode.Service](#apidoc.module.dockerode.Service)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Service (modem, id)](#apidoc.element.dockerode.Service.Service)

#### [module dockerode.Service.prototype](#apidoc.module.dockerode.Service.prototype)
1.  [function <span class="apidocSignatureSpan">dockerode.Service.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Service.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">dockerode.Service.prototype.</span>remove (callback)](#apidoc.element.dockerode.Service.prototype.remove)
1.  [function <span class="apidocSignatureSpan">dockerode.Service.prototype.</span>update (auth, opts, callback)](#apidoc.element.dockerode.Service.prototype.update)

#### [module dockerode.Task](#apidoc.module.dockerode.Task)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Task (modem, id)](#apidoc.element.dockerode.Task.Task)

#### [module dockerode.Task.prototype](#apidoc.module.dockerode.Task.prototype)
1.  [function <span class="apidocSignatureSpan">dockerode.Task.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Task.prototype.inspect)

#### [module dockerode.Volume](#apidoc.module.dockerode.Volume)
1.  [function <span class="apidocSignatureSpan">dockerode.</span>Volume (modem, name)](#apidoc.element.dockerode.Volume.Volume)

#### [module dockerode.Volume.prototype](#apidoc.module.dockerode.Volume.prototype)
1.  [function <span class="apidocSignatureSpan">dockerode.Volume.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Volume.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">dockerode.Volume.prototype.</span>remove (opts, callback)](#apidoc.element.dockerode.Volume.prototype.remove)

#### [module dockerode.util](#apidoc.module.dockerode.util)
1.  [function <span class="apidocSignatureSpan">dockerode.util.</span>extend (obj)](#apidoc.element.dockerode.util.extend)
1.  [function <span class="apidocSignatureSpan">dockerode.util.</span>parseRepositoryTag (input)](#apidoc.element.dockerode.util.parseRepositoryTag)
1.  [function <span class="apidocSignatureSpan">dockerode.util.</span>processArgs (opts, callback, defaultOpts)](#apidoc.element.dockerode.util.processArgs)



# <a name="apidoc.module.dockerode"></a>[module dockerode](#apidoc.module.dockerode)

#### <a name="apidoc.element.dockerode.Container"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Container (modem, id)](#apidoc.element.dockerode.Container)
- description and source-code
```javascript
Container = function (modem, id) {
  this.modem = modem;
  this.id = id;

  this.defaultOptions = {
    top: {},
    start: {},
    commit: {},
    stop: {},
    pause: {},
    unpause: {},
    restart: {},
    resize: {},
    attach: {},
    remove: {},
    copy: {},
    kill: {},
    exec: {},
    rename: {},
    log: {},
    stats: {},
    getArchive: {},
    infoArchive: {},
    putArchive: {},
    update: {}
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Exec"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Exec (modem, id)](#apidoc.element.dockerode.Exec)
- description and source-code
```javascript
Exec = function (modem, id) {
  this.modem = modem;
  this.id = id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Image"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Image (modem, name)](#apidoc.element.dockerode.Image)
- description and source-code
```javascript
Image = function (modem, name) {
  this.modem = modem;
  this.name = name;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Network"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Network (modem, id)](#apidoc.element.dockerode.Network)
- description and source-code
```javascript
Network = function (modem, id) {
  this.modem = modem;
  this.id = id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Node"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Node (modem, id)](#apidoc.element.dockerode.Node)
- description and source-code
```javascript
Node = function (modem, id) {
  this.modem = modem;
  this.id = id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Plugin"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Plugin (modem, name, remote)](#apidoc.element.dockerode.Plugin)
- description and source-code
```javascript
Plugin = function (modem, name, remote) {
  this.modem = modem;
  this.name = name;
  this.remote = remote || name;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Secret"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Secret (modem, id)](#apidoc.element.dockerode.Secret)
- description and source-code
```javascript
Secret = function (modem, id) {
  this.modem = modem;
  this.id = id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Service"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Service (modem, id)](#apidoc.element.dockerode.Service)
- description and source-code
```javascript
Service = function (modem, id) {
  this.modem = modem;
  this.id = id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Task"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Task (modem, id)](#apidoc.element.dockerode.Task)
- description and source-code
```javascript
Task = function (modem, id) {
  this.modem = modem;
  this.id = id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Volume"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Volume (modem, name)](#apidoc.element.dockerode.Volume)
- description and source-code
```javascript
Volume = function (modem, name) {
  this.modem = modem;
  this.name = name;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Container"></a>[module dockerode.Container](#apidoc.module.dockerode.Container)

#### <a name="apidoc.element.dockerode.Container.Container"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Container (modem, id)](#apidoc.element.dockerode.Container.Container)
- description and source-code
```javascript
Container = function (modem, id) {
  this.modem = modem;
  this.id = id;

  this.defaultOptions = {
    top: {},
    start: {},
    commit: {},
    stop: {},
    pause: {},
    unpause: {},
    restart: {},
    resize: {},
    attach: {},
    remove: {},
    copy: {},
    kill: {},
    exec: {},
    rename: {},
    log: {},
    stats: {},
    getArchive: {},
    infoArchive: {},
    putArchive: {},
    update: {}
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Container.prototype"></a>[module dockerode.Container.prototype](#apidoc.module.dockerode.Container.prototype)

#### <a name="apidoc.element.dockerode.Container.prototype.attach"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>attach (opts, callback)](#apidoc.element.dockerode.Container.prototype.attach)
- description and source-code
```javascript
attach = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.attach);

  var optsf = {
    path: '/containers/' + this.id + '/attach?',
    method: 'POST',
    isStream: true,
    hijack: args.opts.hijack,
    openStdin: args.opts.stdin,
    statusCodes: {
      200: true,
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, stream) {
        if (err) {
          return reject(err);
        }
        resolve(stream);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, stream) {
      args.callback(err, stream);
    });
  }
}
```
- example usage
```shell
...

''' js
//tty:true
docker.createContainer({ /*...*/ Tty: true /*...*/ }, function(err, container) {

  /* ... */

  container.attach({stream: true, stdout: true, stderr: true}, function (err, stream) {
    stream.pipe(process.stdout);
  });

  /* ... */
}

//tty:false
...
```

#### <a name="apidoc.element.dockerode.Container.prototype.changes"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>changes (callback)](#apidoc.element.dockerode.Container.prototype.changes)
- description and source-code
```javascript
changes = function (callback) {
  var self = this;
  var optsf = {
    path: '/containers/' + this.id + '/changes',
    method: 'GET',
    statusCodes: {
      200: true,
      404: 'no such container',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.commit"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>commit (opts, callback)](#apidoc.element.dockerode.Container.prototype.commit)
- description and source-code
```javascript
commit = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.commit);

  args.opts.container = this.id;

  var optsf = {
    path: '/commit?',
    method: 'POST',
    statusCodes: {
      200: true, // unofficial, but proxies may return it
      201: true,
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.copy"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>copy (opts, callback)](#apidoc.element.dockerode.Container.prototype.copy)
- description and source-code
```javascript
copy = function (opts, callback) {
  var self = this;
  console.log('container.copy is deprecated since Docker v1.8.x');
  var args = util.processArgs(opts, callback, this.defaultOptions.copy);

  var optsf = {
    path: '/containers/' + this.id + '/copy',
    method: 'POST',
    isStream: true,
    statusCodes: {
      200: true,
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.exec"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>exec (opts, callback)](#apidoc.element.dockerode.Container.prototype.exec)
- description and source-code
```javascript
exec = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.exec);

  var optsf = {
    path: '/containers/' + this.id + '/exec',
    method: 'POST',
    statusCodes: {
      200: true, // unofficial, but proxies may return it
      201: true,
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };


  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(new Exec(self.modem, data.Id));
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      if (err) return args.callback(err, data);
      args.callback(err, new Exec(self.modem, data.Id));
    });
  }
}
```
- example usage
```shell
...
'''

There is also support for [HTTP connection hijacking](https://docs.docker.com/engine/reference/api/docker_remote_api_v1.22/#3-2-
hijacking),
which allows for cleaner interactions with commands that work with stdin and stdout separately.

'''js
docker.createContainer({Tty: false, /*... other options */}, function(err, container) {
  container.exec({Cmd: ['shasum', '-'], AttachStdin: true, AttachStdout: true}, function(err, exec) {
    exec.start({hijack: true, stdin: true}, function(err, stream) {
// shasum can't finish until after its stdin has been closed, telling it that it has
// read all the bytes it needs to sum. Without a socket upgrade, there is no way to
// close the write-side of the stream without also closing the read-side!
fs.createReadStream('node-v5.1.0.tgz', 'binary').pipe(stream);

// Fortunately, we have a regular TCP socket now, so when the readstream finishes and closes our
...
```

#### <a name="apidoc.element.dockerode.Container.prototype.export"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>export (callback)](#apidoc.element.dockerode.Container.prototype.export)
- description and source-code
```javascript
export = function (callback) {
  var self = this;
  var optsf = {
    path: '/containers/' + this.id + '/export',
    method: 'GET',
    isStream: true,
    statusCodes: {
      200: true,
      404: 'no such container',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.getArchive"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>getArchive (opts, callback)](#apidoc.element.dockerode.Container.prototype.getArchive)
- description and source-code
```javascript
getArchive = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.getArchive);

  var optsf = {
    path: '/containers/' + this.id + '/archive?',
    method: 'GET',
    isStream: true,
    statusCodes: {
      200: true,
      400: 'client error, bad parameters',
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.infoArchive"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>infoArchive (opts, callback)](#apidoc.element.dockerode.Container.prototype.infoArchive)
- description and source-code
```javascript
infoArchive = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.infoArchive);

  var optsf = {
    path: '/containers/' + this.id + '/archive?',
    method: 'HEAD',
    isStream: true,
    statusCodes: {
      200: true,
      400: 'client error, bad parameters',
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.inspect"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>inspect (opts, callback)](#apidoc.element.dockerode.Container.prototype.inspect)
- description and source-code
```javascript
inspect = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/containers/' + this.id + '/json?',
    method: 'GET',
    options: args.opts,
    statusCodes: {
      200: true,
      404: 'no such container',
      500: 'server error'
    }
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...
### Manipulating a container:

''' js
// create a container entity. does not query API
var container = docker.getContainer('71501a8ab0f8');

// query API for container info
container.inspect(function (err, data) {
  console.log(data);
});

container.start(function (err, data) {
  console.log(data);
});
...
```

#### <a name="apidoc.element.dockerode.Container.prototype.kill"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>kill (opts, callback)](#apidoc.element.dockerode.Container.prototype.kill)
- description and source-code
```javascript
kill = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.kill);

  var optsf = {
    path: '/containers/' + this.id + '/kill?',
    method: 'POST',
    statusCodes: {
      200: true, // unofficial, but proxies may return it
      204: true,
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.logs"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>logs (opts, callback)](#apidoc.element.dockerode.Container.prototype.logs)
- description and source-code
```javascript
logs = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.log);

  var optsf = {
    path: '/containers/' + this.id + '/logs?',
    method: 'GET',
    isStream: true,
    statusCodes: {
      200: true,
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.pause"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>pause (opts, callback)](#apidoc.element.dockerode.Container.prototype.pause)
- description and source-code
```javascript
pause = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.pause);

  var optsf = {
    path: '/containers/' + this.id + '/pause',
    method: 'POST',
    statusCodes: {
      200: true, // unofficial, but proxies may return it
      204: true,
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.putArchive"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>putArchive (file, opts, callback)](#apidoc.element.dockerode.Container.prototype.putArchive)
- description and source-code
```javascript
putArchive = function (file, opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.putArchive);

  var optsf = {
    path: '/containers/' + this.id + '/archive?',
    method: 'PUT',
    file: file,
    isStream: true,
    statusCodes: {
      200: true,
      400: 'client error, bad parameters',
      403: 'client error, permission denied',
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.remove"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>remove (opts, callback)](#apidoc.element.dockerode.Container.prototype.remove)
- description and source-code
```javascript
remove = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.remove);

  var optsf = {
    path: '/containers/' + this.id + '?',
    method: 'DELETE',
    statusCodes: {
      200: true, // unofficial, but proxies may return it
      204: true,
      400: 'bad parameter',
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...
console.log(data);
});

container.start(function (err, data) {
console.log(data);
});

container.remove(function (err, data) {
console.log(data);
});

// promises are supported
docker.createContainer({
Image: 'ubuntu',
AttachStdin: false,
...
```

#### <a name="apidoc.element.dockerode.Container.prototype.rename"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>rename (opts, callback)](#apidoc.element.dockerode.Container.prototype.rename)
- description and source-code
```javascript
rename = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.rename);

  var optsf = {
    path: '/containers/' + this.id + '/rename?',
    method: 'POST',
    statusCodes: {
      200: true,
      204: true,
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.resize"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>resize (opts, callback)](#apidoc.element.dockerode.Container.prototype.resize)
- description and source-code
```javascript
resize = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.resize);

  var optsf = {
    path: '/containers/' + this.id + '/resize?',
    method: 'POST',
    statusCodes: {
      200: true,
      400: 'bad parameter',
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...
Tty: true,
Cmd: ['/bin/bash', '-c', 'tail -f /var/log/dmesg'],
OpenStdin: false,
StdinOnce: false
}).then(function(container) {
return container.start();
}).then(function(container) {
return container.resize({
  h: process.stdout.rows,
  w: process.stdout.columns
});
}).then(function(container) {
return container.stop();
}).then(function(container) {
return container.remove();
...
```

#### <a name="apidoc.element.dockerode.Container.prototype.restart"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>restart (opts, callback)](#apidoc.element.dockerode.Container.prototype.restart)
- description and source-code
```javascript
restart = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.restart);

  var optsf = {
    path: '/containers/' + this.id + '/restart',
    method: 'POST',
    statusCodes: {
      200: true, // unofficial, but proxies may return it
      204: true,
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.start"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>start (opts, callback)](#apidoc.element.dockerode.Container.prototype.start)
- description and source-code
```javascript
start = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.start);

  var optsf = {
    path: '/containers/' + this.id + '/start',
    method: 'POST',
    statusCodes: {
      200: true, // unofficial, but proxies may return it
      204: true,
      304: 'container already started',
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...
var container = docker.getContainer('71501a8ab0f8');

// query API for container info
container.inspect(function (err, data) {
  console.log(data);
});

container.start(function (err, data) {
  console.log(data);
});

container.remove(function (err, data) {
  console.log(data);
});
...
```

#### <a name="apidoc.element.dockerode.Container.prototype.stats"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>stats (opts, callback)](#apidoc.element.dockerode.Container.prototype.stats)
- description and source-code
```javascript
stats = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.stats);
  var isStream = true;
  if (args.opts.stream === false) {
    isStream = false;
  }
  var optsf = {
    path: '/containers/' + this.id + '/stats?',
    method: 'GET',
    isStream: isStream,
    statusCodes: {
      200: true,
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.stop"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>stop (opts, callback)](#apidoc.element.dockerode.Container.prototype.stop)
- description and source-code
```javascript
stop = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.stop);

  var optsf = {
    path: '/containers/' + this.id + '/stop?',
    method: 'POST',
    statusCodes: {
      200: true, // unofficial, but proxies may return it
      204: true,
      304: 'container already stopped',
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...
  return container.start();
}).then(function(container) {
  return container.resize({
    h: process.stdout.rows,
    w: process.stdout.columns
  });
}).then(function(container) {
  return container.stop();
}).then(function(container) {
  return container.remove();
}).then(function(data) {
  console.log('container removed');
}).catch(function(err) {
  console.log(err);
});
...
```

#### <a name="apidoc.element.dockerode.Container.prototype.top"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>top (opts, callback)](#apidoc.element.dockerode.Container.prototype.top)
- description and source-code
```javascript
top = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.top);

  var optsf = {
    path: '/containers/' + this.id + '/top?',
    method: 'GET',
    statusCodes: {
      200: true,
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.unpause"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>unpause (opts, callback)](#apidoc.element.dockerode.Container.prototype.unpause)
- description and source-code
```javascript
unpause = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.unpause);

  var optsf = {
    path: '/containers/' + this.id + '/unpause',
    method: 'POST',
    statusCodes: {
      200: true, // unofficial, but proxies may return it
      204: true,
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.update"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>update (opts, callback)](#apidoc.element.dockerode.Container.prototype.update)
- description and source-code
```javascript
update = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback, this.defaultOptions.update);

  var optsf = {
    path: '/containers/' + this.id + '/update',
    method: 'POST',
    statusCodes: {
      200: true,
      204: true,
      400: 'bad parameter',
      404: 'no such container',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Container.prototype.wait"></a>[function <span class="apidocSignatureSpan">dockerode.Container.prototype.</span>wait (callback)](#apidoc.element.dockerode.Container.prototype.wait)
- description and source-code
```javascript
wait = function (callback) {
  var self = this;
  var optsf = {
    path: '/containers/' + this.id + '/wait',
    method: 'POST',
    statusCodes: {
      200: true,
      400: 'bad parameter',
      404: 'no such container',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Exec"></a>[module dockerode.Exec](#apidoc.module.dockerode.Exec)

#### <a name="apidoc.element.dockerode.Exec.Exec"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Exec (modem, id)](#apidoc.element.dockerode.Exec.Exec)
- description and source-code
```javascript
Exec = function (modem, id) {
  this.modem = modem;
  this.id = id;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Exec.prototype"></a>[module dockerode.Exec.prototype](#apidoc.module.dockerode.Exec.prototype)

#### <a name="apidoc.element.dockerode.Exec.prototype.inspect"></a>[function <span class="apidocSignatureSpan">dockerode.Exec.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Exec.prototype.inspect)
- description and source-code
```javascript
inspect = function (callback) {
  var self = this;

  var optsf = {
    path: '/exec/' + this.id + '/json',
    method: 'GET',
    statusCodes: {
      200: true,
      404: 'no such exec',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      if (err) return callback(err, data);
      callback(err, data);
    });
  }
}
```
- example usage
```shell
...
### Manipulating a container:

''' js
// create a container entity. does not query API
var container = docker.getContainer('71501a8ab0f8');

// query API for container info
container.inspect(function (err, data) {
  console.log(data);
});

container.start(function (err, data) {
  console.log(data);
});
...
```

#### <a name="apidoc.element.dockerode.Exec.prototype.resize"></a>[function <span class="apidocSignatureSpan">dockerode.Exec.prototype.</span>resize (opts, callback)](#apidoc.element.dockerode.Exec.prototype.resize)
- description and source-code
```javascript
resize = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/exec/' + this.id + '/resize?',
    method: 'POST',
    statusCodes: {
      200: true,
      404: 'no such exec',
      500: 'container not running'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      if (err) return args.callback(err, data);
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...
Tty: true,
Cmd: ['/bin/bash', '-c', 'tail -f /var/log/dmesg'],
OpenStdin: false,
StdinOnce: false
}).then(function(container) {
return container.start();
}).then(function(container) {
return container.resize({
  h: process.stdout.rows,
  w: process.stdout.columns
});
}).then(function(container) {
return container.stop();
}).then(function(container) {
return container.remove();
...
```

#### <a name="apidoc.element.dockerode.Exec.prototype.start"></a>[function <span class="apidocSignatureSpan">dockerode.Exec.prototype.</span>start (opts, callback)](#apidoc.element.dockerode.Exec.prototype.start)
- description and source-code
```javascript
start = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/exec/' + this.id + '/start',
    method: 'POST',
    isStream: true,
    hijack: args.opts.hijack,
    openStdin: args.opts.stdin,
    statusCodes: {
      200: true,
      204: true,
      404: 'no such exec',
      409: 'container stopped/paused',
      500: 'container not running'
    },
    options: args.opts
  };


  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      if (err) return args.callback(err, data);
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...
var container = docker.getContainer('71501a8ab0f8');

// query API for container info
container.inspect(function (err, data) {
  console.log(data);
});

container.start(function (err, data) {
  console.log(data);
});

container.remove(function (err, data) {
  console.log(data);
});
...
```



# <a name="apidoc.module.dockerode.Image"></a>[module dockerode.Image](#apidoc.module.dockerode.Image)

#### <a name="apidoc.element.dockerode.Image.Image"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Image (modem, name)](#apidoc.element.dockerode.Image.Image)
- description and source-code
```javascript
Image = function (modem, name) {
  this.modem = modem;
  this.name = name;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Image.prototype"></a>[module dockerode.Image.prototype](#apidoc.module.dockerode.Image.prototype)

#### <a name="apidoc.element.dockerode.Image.prototype.get"></a>[function <span class="apidocSignatureSpan">dockerode.Image.prototype.</span>get (callback)](#apidoc.element.dockerode.Image.prototype.get)
- description and source-code
```javascript
get = function (callback) {
  var self = this;
  var opts = {
    path: '/images/' + this.name + '/get',
    method: 'GET',
    isStream: true,
    statusCodes: {
      200: true,
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(opts, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(opts, function(err, data) {
      if (err) return callback(err, data);
      callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Image.prototype.history"></a>[function <span class="apidocSignatureSpan">dockerode.Image.prototype.</span>history (callback)](#apidoc.element.dockerode.Image.prototype.history)
- description and source-code
```javascript
history = function (callback) {
  var self = this;
  var opts = {
    path: '/images/' + this.name + '/history',
    method: 'GET',
    statusCodes: {
      200: true,
      404: 'no such image',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(opts, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(opts, function(err, data) {
      if (err) return callback(err, data);
      callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Image.prototype.inspect"></a>[function <span class="apidocSignatureSpan">dockerode.Image.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Image.prototype.inspect)
- description and source-code
```javascript
inspect = function (callback) {
  var self = this;

  var opts = {
    path: '/images/' + this.name + '/json',
    method: 'GET',
    statusCodes: {
      200: true,
      404: 'no such image',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(opts, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(opts, function(err, data) {
      if (err) return callback(err, data);
      callback(err, data);
    });
  }
}
```
- example usage
```shell
...
### Manipulating a container:

''' js
// create a container entity. does not query API
var container = docker.getContainer('71501a8ab0f8');

// query API for container info
container.inspect(function (err, data) {
  console.log(data);
});

container.start(function (err, data) {
  console.log(data);
});
...
```

#### <a name="apidoc.element.dockerode.Image.prototype.push"></a>[function <span class="apidocSignatureSpan">dockerode.Image.prototype.</span>push (opts, callback, auth)](#apidoc.element.dockerode.Image.prototype.push)
- description and source-code
```javascript
push = function (opts, callback, auth) {
  var self = this;
  var args = util.processArgs(opts, callback);
  var isStream = true;
  if (args.opts.stream === false) {
    isStream = false;
  }
  var optsf = {
    path: '/images/' + this.name + '/push?',
    method: 'POST',
    options: args.opts,
    authconfig: args.opts.authconfig || auth,
    isStream: isStream,
    statusCodes: {
      200: true,
      404: 'no such image',
      500: 'server error'
    }
  };

  delete optsf.options.authconfig;

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Image.prototype.remove"></a>[function <span class="apidocSignatureSpan">dockerode.Image.prototype.</span>remove (opts, callback)](#apidoc.element.dockerode.Image.prototype.remove)
- description and source-code
```javascript
remove = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);


  var optsf = {
    path: '/images/' + this.name + '?',
    method: 'DELETE',
    statusCodes: {
      200: true,
      404: 'no such image',
      409: 'conflict',
      500: 'server error'
    },
    options: args.opts
  };


  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...
console.log(data);
});

container.start(function (err, data) {
console.log(data);
});

container.remove(function (err, data) {
console.log(data);
});

// promises are supported
docker.createContainer({
Image: 'ubuntu',
AttachStdin: false,
...
```

#### <a name="apidoc.element.dockerode.Image.prototype.tag"></a>[function <span class="apidocSignatureSpan">dockerode.Image.prototype.</span>tag (opts, callback)](#apidoc.element.dockerode.Image.prototype.tag)
- description and source-code
```javascript
tag = function (opts, callback) {
  var self = this;
  var optsf = {
    path: '/images/' + this.name + '/tag?',
    method: 'POST',
    options: opts,
    statusCodes: {
      200: true, // unofficial, but proxies may return it
      201: true,
      400: 'bad parameter',
      404: 'no such image',
      409: 'conflict',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Network"></a>[module dockerode.Network](#apidoc.module.dockerode.Network)

#### <a name="apidoc.element.dockerode.Network.Network"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Network (modem, id)](#apidoc.element.dockerode.Network.Network)
- description and source-code
```javascript
Network = function (modem, id) {
  this.modem = modem;
  this.id = id;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Network.prototype"></a>[module dockerode.Network.prototype](#apidoc.module.dockerode.Network.prototype)

#### <a name="apidoc.element.dockerode.Network.prototype.connect"></a>[function <span class="apidocSignatureSpan">dockerode.Network.prototype.</span>connect (opts, callback)](#apidoc.element.dockerode.Network.prototype.connect)
- description and source-code
```javascript
connect = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/networks/' + this.id + '/connect',
    method: 'POST',
    statusCodes: {
      200: true,
      201: true,
      404: 'network or container is not found',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Network.prototype.disconnect"></a>[function <span class="apidocSignatureSpan">dockerode.Network.prototype.</span>disconnect (opts, callback)](#apidoc.element.dockerode.Network.prototype.disconnect)
- description and source-code
```javascript
disconnect = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/networks/' + this.id + '/disconnect',
    method: 'POST',
    statusCodes: {
      200: true,
      201: true,
      404: 'network or container is not found',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Network.prototype.inspect"></a>[function <span class="apidocSignatureSpan">dockerode.Network.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Network.prototype.inspect)
- description and source-code
```javascript
inspect = function (callback) {
  var self = this;

  var opts = {
    path: '/networks/' + this.id,
    method: 'GET',
    statusCodes: {
      200: true,
      404: 'no such network',
      500: 'server error'
    }
  };


  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(opts, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(opts, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
...
### Manipulating a container:

''' js
// create a container entity. does not query API
var container = docker.getContainer('71501a8ab0f8');

// query API for container info
container.inspect(function (err, data) {
  console.log(data);
});

container.start(function (err, data) {
  console.log(data);
});
...
```

#### <a name="apidoc.element.dockerode.Network.prototype.remove"></a>[function <span class="apidocSignatureSpan">dockerode.Network.prototype.</span>remove (opts, callback)](#apidoc.element.dockerode.Network.prototype.remove)
- description and source-code
```javascript
remove = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/networks/' + this.id,
    method: 'DELETE',
    statusCodes: {
      200: true,
      204: true,
      404: 'no such network',
      409: 'conflict',
      500: 'server error'
    },
    options: args.opts
  };


  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...
console.log(data);
});

container.start(function (err, data) {
console.log(data);
});

container.remove(function (err, data) {
console.log(data);
});

// promises are supported
docker.createContainer({
Image: 'ubuntu',
AttachStdin: false,
...
```



# <a name="apidoc.module.dockerode.Node"></a>[module dockerode.Node](#apidoc.module.dockerode.Node)

#### <a name="apidoc.element.dockerode.Node.Node"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Node (modem, id)](#apidoc.element.dockerode.Node.Node)
- description and source-code
```javascript
Node = function (modem, id) {
  this.modem = modem;
  this.id = id;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Node.prototype"></a>[module dockerode.Node.prototype](#apidoc.module.dockerode.Node.prototype)

#### <a name="apidoc.element.dockerode.Node.prototype.inspect"></a>[function <span class="apidocSignatureSpan">dockerode.Node.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Node.prototype.inspect)
- description and source-code
```javascript
inspect = function (callback) {
  var self = this;

  var optsf = {
    path: '/nodes/' + this.id,
    method: 'GET',
    statusCodes: {
      200: true,
      404: 'no such node',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
...
### Manipulating a container:

''' js
// create a container entity. does not query API
var container = docker.getContainer('71501a8ab0f8');

// query API for container info
container.inspect(function (err, data) {
  console.log(data);
});

container.start(function (err, data) {
  console.log(data);
});
...
```

#### <a name="apidoc.element.dockerode.Node.prototype.remove"></a>[function <span class="apidocSignatureSpan">dockerode.Node.prototype.</span>remove (callback)](#apidoc.element.dockerode.Node.prototype.remove)
- description and source-code
```javascript
remove = function (callback) {
  var self = this;

  var optsf = {
    path: '/nodes/' + this.id,
    method: 'DELETE',
    statusCodes: {
      200: true,
      404: 'no such node',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
...
console.log(data);
});

container.start(function (err, data) {
console.log(data);
});

container.remove(function (err, data) {
console.log(data);
});

// promises are supported
docker.createContainer({
Image: 'ubuntu',
AttachStdin: false,
...
```

#### <a name="apidoc.element.dockerode.Node.prototype.update"></a>[function <span class="apidocSignatureSpan">dockerode.Node.prototype.</span>update (opts, callback)](#apidoc.element.dockerode.Node.prototype.update)
- description and source-code
```javascript
update = function (opts, callback) {
  var self = this;
  if (!callback && typeof opts === 'function') {
    callback = opts;
  }

  var optsf = {
    path: '/nodes/' + this.id + '/update?',
    method: 'POST',
    statusCodes: {
      200: true,
      404: 'no such node',
      406: 'node is not part of a swarm',
      500: 'server error'
    },
    options: opts
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Plugin"></a>[module dockerode.Plugin](#apidoc.module.dockerode.Plugin)

#### <a name="apidoc.element.dockerode.Plugin.Plugin"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Plugin (modem, name, remote)](#apidoc.element.dockerode.Plugin.Plugin)
- description and source-code
```javascript
Plugin = function (modem, name, remote) {
  this.modem = modem;
  this.name = name;
  this.remote = remote || name;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Plugin.prototype"></a>[module dockerode.Plugin.prototype](#apidoc.module.dockerode.Plugin.prototype)

#### <a name="apidoc.element.dockerode.Plugin.prototype.configure"></a>[function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>configure (opts, callback)](#apidoc.element.dockerode.Plugin.prototype.configure)
- description and source-code
```javascript
configure = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/plugins/' + this.name + '/set',
    method: 'POST',
    statusCodes: {
      200: true,
      404: 'plugin not installed',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Plugin.prototype.disable"></a>[function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>disable (opts, callback)](#apidoc.element.dockerode.Plugin.prototype.disable)
- description and source-code
```javascript
disable = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/plugins/' + this.name + '/disable',
    method: 'POST',
    statusCodes: {
      200: true,
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Plugin.prototype.enable"></a>[function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>enable (opts, callback)](#apidoc.element.dockerode.Plugin.prototype.enable)
- description and source-code
```javascript
enable = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/plugins/' + this.name + '/enable?',
    method: 'POST',
    statusCodes: {
      200: true,
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Plugin.prototype.inspect"></a>[function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Plugin.prototype.inspect)
- description and source-code
```javascript
inspect = function (callback) {
  var self = this;

  var optsf = {
    path: '/plugins/' + this.name,
    method: 'GET',
    statusCodes: {
      200: true,
      404: 'plugin is not installed',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
...
### Manipulating a container:

''' js
// create a container entity. does not query API
var container = docker.getContainer('71501a8ab0f8');

// query API for container info
container.inspect(function (err, data) {
  console.log(data);
});

container.start(function (err, data) {
  console.log(data);
});
...
```

#### <a name="apidoc.element.dockerode.Plugin.prototype.privileges"></a>[function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>privileges (callback)](#apidoc.element.dockerode.Plugin.prototype.privileges)
- description and source-code
```javascript
privileges = function (callback) {
  var self = this;
  var optsf = {
    path: '/plugins/privileges?',
    method: 'GET',
    options: {
      'remote': this.remote
    },
    statusCodes: {
      200: true,
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Plugin.prototype.pull"></a>[function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>pull (opts, callback)](#apidoc.element.dockerode.Plugin.prototype.pull)
- description and source-code
```javascript
pull = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  if(args.opts._query && !args.opts._query.name) {
    args.opts._query.name = this.name;
  }
  if(args.opts._query && !args.opts._query.remote) {
    args.opts._query.remote = this.remote;
  }

  var optsf = {
    path: '/plugins/pull?',
    method: 'POST',
    isStream: true,
    options: args.opts,
    statusCodes: {
      200: true, // unofficial, but proxies may return it
      204: true,
      500: 'server error'
    }
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...

* 'repoTag' - container image name (optionally with tag)
  'myrepo/myname:withtag'
* 'opts' - extra options passed to create image.
* 'callback' - callback called when execution ends.

''' js
docker.pull('myrepo/myname:tag', function (err, stream) {
  // streaming output from pull...
});
'''

#### Pull from private repos

'docker-modem' already base64 encodes the necessary auth object for you.
...
```

#### <a name="apidoc.element.dockerode.Plugin.prototype.push"></a>[function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>push (opts, callback)](#apidoc.element.dockerode.Plugin.prototype.push)
- description and source-code
```javascript
push = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/plugins/' + this.name + '/push',
    method: 'POST',
    statusCodes: {
      200: true,
      404: 'plugin not installed',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.Plugin.prototype.remove"></a>[function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>remove (opts, callback)](#apidoc.element.dockerode.Plugin.prototype.remove)
- description and source-code
```javascript
remove = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/plugins/' + this.name + '?',
    method: 'DELETE',
    statusCodes: {
      200: true,
      404: 'plugin is not installed',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      if (err) return args.callback(err, data);
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...
console.log(data);
});

container.start(function (err, data) {
console.log(data);
});

container.remove(function (err, data) {
console.log(data);
});

// promises are supported
docker.createContainer({
Image: 'ubuntu',
AttachStdin: false,
...
```

#### <a name="apidoc.element.dockerode.Plugin.prototype.upgrade"></a>[function <span class="apidocSignatureSpan">dockerode.Plugin.prototype.</span>upgrade (auth, opts, callback)](#apidoc.element.dockerode.Plugin.prototype.upgrade)
- description and source-code
```javascript
upgrade = function (auth, opts, callback) {
  var self = this;
  if (!callback && typeof opts === 'function') {
    callback = opts;
    opts = auth;
    auth = opts.authconfig || undefined;
  }

  var optsf = {
    path: '/plugins/' + this.name + '/upgrade?',
    method: 'POST',
    statusCodes: {
      200: true,
      204: true,
      404: 'plugin not installed',
      500: 'server error'
    },
    authconfig: auth,
    options: opts
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Secret"></a>[module dockerode.Secret](#apidoc.module.dockerode.Secret)

#### <a name="apidoc.element.dockerode.Secret.Secret"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Secret (modem, id)](#apidoc.element.dockerode.Secret.Secret)
- description and source-code
```javascript
Secret = function (modem, id) {
  this.modem = modem;
  this.id = id;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Secret.prototype"></a>[module dockerode.Secret.prototype](#apidoc.module.dockerode.Secret.prototype)

#### <a name="apidoc.element.dockerode.Secret.prototype.inspect"></a>[function <span class="apidocSignatureSpan">dockerode.Secret.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Secret.prototype.inspect)
- description and source-code
```javascript
inspect = function (callback) {
  var self = this;

  var optsf = {
    path: '/secrets/' + this.id,
    method: 'GET',
    statusCodes: {
      200: true,
      404: 'secret not found',
      406: 'node is not part of a swarm',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
...
### Manipulating a container:

''' js
// create a container entity. does not query API
var container = docker.getContainer('71501a8ab0f8');

// query API for container info
container.inspect(function (err, data) {
  console.log(data);
});

container.start(function (err, data) {
  console.log(data);
});
...
```

#### <a name="apidoc.element.dockerode.Secret.prototype.remove"></a>[function <span class="apidocSignatureSpan">dockerode.Secret.prototype.</span>remove (opts, callback)](#apidoc.element.dockerode.Secret.prototype.remove)
- description and source-code
```javascript
remove = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/secrets/' + this.id,
    method: 'DELETE',
    statusCodes: {
      200: true,
      204: true,
      404: 'secret not found',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...
console.log(data);
});

container.start(function (err, data) {
console.log(data);
});

container.remove(function (err, data) {
console.log(data);
});

// promises are supported
docker.createContainer({
Image: 'ubuntu',
AttachStdin: false,
...
```

#### <a name="apidoc.element.dockerode.Secret.prototype.update"></a>[function <span class="apidocSignatureSpan">dockerode.Secret.prototype.</span>update (opts, callback)](#apidoc.element.dockerode.Secret.prototype.update)
- description and source-code
```javascript
update = function (opts, callback) {
  var self = this;
  if (!callback && typeof opts === 'function') {
    callback = opts;
  }

  var optsf = {
    path: '/secrets/' + this.id + '/update?',
    method: 'POST',
    statusCodes: {
      200: true,
      404: 'secret not found',
      500: 'server error'
    },
    options: opts
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Service"></a>[module dockerode.Service](#apidoc.module.dockerode.Service)

#### <a name="apidoc.element.dockerode.Service.Service"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Service (modem, id)](#apidoc.element.dockerode.Service.Service)
- description and source-code
```javascript
Service = function (modem, id) {
  this.modem = modem;
  this.id = id;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Service.prototype"></a>[module dockerode.Service.prototype](#apidoc.module.dockerode.Service.prototype)

#### <a name="apidoc.element.dockerode.Service.prototype.inspect"></a>[function <span class="apidocSignatureSpan">dockerode.Service.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Service.prototype.inspect)
- description and source-code
```javascript
inspect = function (callback) {
  var self = this;

  var optsf = {
    path: '/services/' + this.id,
    method: 'GET',
    statusCodes: {
      200: true,
      404: 'no such service',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
...
### Manipulating a container:

''' js
// create a container entity. does not query API
var container = docker.getContainer('71501a8ab0f8');

// query API for container info
container.inspect(function (err, data) {
  console.log(data);
});

container.start(function (err, data) {
  console.log(data);
});
...
```

#### <a name="apidoc.element.dockerode.Service.prototype.remove"></a>[function <span class="apidocSignatureSpan">dockerode.Service.prototype.</span>remove (callback)](#apidoc.element.dockerode.Service.prototype.remove)
- description and source-code
```javascript
remove = function (callback) {
  var self = this;
  var optsf = {
    path: '/services/' + this.id,
    method: 'DELETE',
    statusCodes: {
      200: true,
      204: true,
      404: 'no such service',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
...
console.log(data);
});

container.start(function (err, data) {
console.log(data);
});

container.remove(function (err, data) {
console.log(data);
});

// promises are supported
docker.createContainer({
Image: 'ubuntu',
AttachStdin: false,
...
```

#### <a name="apidoc.element.dockerode.Service.prototype.update"></a>[function <span class="apidocSignatureSpan">dockerode.Service.prototype.</span>update (auth, opts, callback)](#apidoc.element.dockerode.Service.prototype.update)
- description and source-code
```javascript
update = function (auth, opts, callback) {
  var self = this;
  if (!callback && typeof opts === 'function') {
    callback = opts;
    opts = auth;
    auth = opts.authconfig || undefined;
  }

  var optsf = {
    path: '/services/' + this.id + '/update?',
    method: 'POST',
    statusCodes: {
      200: true,
      404: 'no such service',
      500: 'server error'
    },
    authconfig: auth,
    options: opts
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        self.output = data;
        resolve(self);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Task"></a>[module dockerode.Task](#apidoc.module.dockerode.Task)

#### <a name="apidoc.element.dockerode.Task.Task"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Task (modem, id)](#apidoc.element.dockerode.Task.Task)
- description and source-code
```javascript
Task = function (modem, id) {
  this.modem = modem;
  this.id = id;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Task.prototype"></a>[module dockerode.Task.prototype](#apidoc.module.dockerode.Task.prototype)

#### <a name="apidoc.element.dockerode.Task.prototype.inspect"></a>[function <span class="apidocSignatureSpan">dockerode.Task.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Task.prototype.inspect)
- description and source-code
```javascript
inspect = function (callback) {
  var self = this;

  var optsf = {
    path: '/tasks/' + this.id,
    method: 'GET',
    statusCodes: {
      200: true,
      404: 'unknown task',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
...
### Manipulating a container:

''' js
// create a container entity. does not query API
var container = docker.getContainer('71501a8ab0f8');

// query API for container info
container.inspect(function (err, data) {
  console.log(data);
});

container.start(function (err, data) {
  console.log(data);
});
...
```



# <a name="apidoc.module.dockerode.Volume"></a>[module dockerode.Volume](#apidoc.module.dockerode.Volume)

#### <a name="apidoc.element.dockerode.Volume.Volume"></a>[function <span class="apidocSignatureSpan">dockerode.</span>Volume (modem, name)](#apidoc.element.dockerode.Volume.Volume)
- description and source-code
```javascript
Volume = function (modem, name) {
  this.modem = modem;
  this.name = name;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dockerode.Volume.prototype"></a>[module dockerode.Volume.prototype](#apidoc.module.dockerode.Volume.prototype)

#### <a name="apidoc.element.dockerode.Volume.prototype.inspect"></a>[function <span class="apidocSignatureSpan">dockerode.Volume.prototype.</span>inspect (callback)](#apidoc.element.dockerode.Volume.prototype.inspect)
- description and source-code
```javascript
inspect = function (callback) {
  var self = this;

  var optsf = {
    path: '/volumes/' + this.name,
    method: 'GET',
    statusCodes: {
      200: true,
      404: 'no such volume',
      500: 'server error'
    }
  };

  if(callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      callback(err, data);
    });
  }
}
```
- example usage
```shell
...
### Manipulating a container:

''' js
// create a container entity. does not query API
var container = docker.getContainer('71501a8ab0f8');

// query API for container info
container.inspect(function (err, data) {
  console.log(data);
});

container.start(function (err, data) {
  console.log(data);
});
...
```

#### <a name="apidoc.element.dockerode.Volume.prototype.remove"></a>[function <span class="apidocSignatureSpan">dockerode.Volume.prototype.</span>remove (opts, callback)](#apidoc.element.dockerode.Volume.prototype.remove)
- description and source-code
```javascript
remove = function (opts, callback) {
  var self = this;
  var args = util.processArgs(opts, callback);

  var optsf = {
    path: '/volumes/' + this.name,
    method: 'DELETE',
    statusCodes: {
      204: true,
      404: 'no such volume',
      409: 'conflict',
      500: 'server error'
    },
    options: args.opts
  };

  if(args.callback === undefined) {
    return new this.modem.Promise(function(resolve, reject) {
      self.modem.dial(optsf, function(err, data) {
        if (err) {
          return reject(err);
        }
        resolve(data);
      });
    });
  } else {
    this.modem.dial(optsf, function(err, data) {
      args.callback(err, data);
    });
  }
}
```
- example usage
```shell
...
console.log(data);
});

container.start(function (err, data) {
console.log(data);
});

container.remove(function (err, data) {
console.log(data);
});

// promises are supported
docker.createContainer({
Image: 'ubuntu',
AttachStdin: false,
...
```



# <a name="apidoc.module.dockerode.util"></a>[module dockerode.util](#apidoc.module.dockerode.util)

#### <a name="apidoc.element.dockerode.util.extend"></a>[function <span class="apidocSignatureSpan">dockerode.util.</span>extend (obj)](#apidoc.element.dockerode.util.extend)
- description and source-code
```javascript
extend = function (obj) {
  each.call(slice.call(arguments, 1), function(source) {
    if (source) {
      for (var prop in source) {
        obj[prop] = source[prop];
      }
    }
  });
  return obj;
}
```
- example usage
```shell
...
module.exports.processArgs = function(opts, callback, defaultOpts) {
 if (!callback && typeof opts === 'function') {
   callback = opts;
   opts = null;
 }
 return {
   callback: callback,
   opts: module.exports.extend({}, defaultOpts, opts)
 };
};


/**
* Parse the given repo tag name (as a string) and break it out into repo/tag pair.
* // if given the input http://localhost:8080/woot:latest
...
```

#### <a name="apidoc.element.dockerode.util.parseRepositoryTag"></a>[function <span class="apidocSignatureSpan">dockerode.util.</span>parseRepositoryTag (input)](#apidoc.element.dockerode.util.parseRepositoryTag)
- description and source-code
```javascript
parseRepositoryTag = function (input) {
  var separatorPos;
  var digestPos = input.indexOf('@');
  var colonPos = input.lastIndexOf(':');
  // @ symbol is more important
  if (digestPos >= 0) {
    separatorPos = digestPos;
  } else if (colonPos >= 0) {
    separatorPos = colonPos;
  } else {
    // no colon nor @
    return {
      repository: input
    };
  }

  // last colon is either the tag (or part of a port designation)
  var tag = input.slice(separatorPos + 1);

  // if it contains a / its not a tag and is part of the url
  if (tag.indexOf('/') === -1) {
    return {
      repository: input.slice(0, separatorPos),
      tag: tag
    };
  }

  return {
    repository: input
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dockerode.util.processArgs"></a>[function <span class="apidocSignatureSpan">dockerode.util.</span>processArgs (opts, callback, defaultOpts)](#apidoc.element.dockerode.util.processArgs)
- description and source-code
```javascript
processArgs = function (opts, callback, defaultOpts) {
  if (!callback && typeof opts === 'function') {
    callback = opts;
    opts = null;
  }
  return {
    callback: callback,
    opts: module.exports.extend({}, defaultOpts, opts)
  };
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
