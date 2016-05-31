Example for https://github.com/jspm/jspm-cli/issues/1859
```bash
 jakeniemiec@Sat  ~/RubymineProjects  git clone git@github.com:jakeNiemiec/jspmsandbox.git
Cloning into 'jspmsandbox'...
remote: Counting objects: 15, done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 15 (delta 1), reused 15 (delta 1), pack-reused 0
Receiving objects: 100% (15/15), done.
Resolving deltas: 100% (1/1), done.
Checking connectivity... done.
 jakeniemiec@Sat  ~/RubymineProjects  cd jspmsandbox
 jakeniemiec@Sat  ~/RubymineProjects/jspmsandbox   master  npm i
jspmsandbox@1.0.0 /Users/jakeniemiec/RubymineProjects/jspmsandbox
├─┬ jspm@0.17.0-beta.16
  #(long dep tree excluded)
└── typescript@1.8.10

npm WARN jspmsandbox@1.0.0 No description
npm WARN jspmsandbox@1.0.0 No repository field.
 jakeniemiec@Sat  ~/RubymineProjects/jspmsandbox   master  jspm i
     Updating registry cache...
ok   Installed dev dependency npm:os-browserify@^0.2.0 (0.2.1)
ok   Installed dev dependency os to github:jspm/nodelibs-os@^0.2.0-alpha (0.2.0-alpha)
ok   Installed dev dependency npm:typescript@^1.8.7 (1.8.10)
ok   Installed dev dependency plugin-typescript to github:frankwallis/plugin-typescript@^4.0.16 (4.0.16)
     Install tree has no forks.
     Looking up loader files...
       system-polyfills.js
       system.js.map
       system.js
       system.src.js
       system-polyfills.src.js
       system-polyfills.js.map

     Using loader versions:
       systemjs@0.19.29
ok   Loader files downloaded successfully

ok   Install complete.
 jakeniemiec@Sat  ~/RubymineProjects/jspmsandbox   master  tsc
 jakeniemiec@Sat  ~/RubymineProjects/jspmsandbox   master  jspm bundle jspmsandbox
     Building the bundle tree for jspmsandbox...

err  Source jspmsandbox/jspmsandbox.js has multiple anonymous System.register calls.
```
