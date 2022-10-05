# Bug report for Vitest

This project is just a normal output from `npm create svelte@latest my-app` + `npx @preset/cli davipon/svelte-add-vitest` to add vitest.

```
$ npm version

{
  'vitest-bug-ws-close': '0.0.1',
  npm: '8.15.0',
  node: '18.7.0',
  v8: '10.2.154.13-node.9',
  uv: '1.43.0',
  zlib: '1.2.11',
  brotli: '1.0.9',
  ares: '1.18.1',
  modules: '108',
  nghttp2: '1.47.0',
  napi: '8',
  llhttp: '6.0.7',
  openssl: '3.0.5+quic',
  cldr: '41.0',
  icu: '71.1',
  tz: '2022a',
  unicode: '14.0',
  ngtcp2: '0.1.0-DEV',
  nghttp3: '0.1.0-DEV'
}

# VS Code version
$ code -v

1.71.2
74b1f979648cc44d385a2286793c226e611f59e7
x64

# Plugin versions
$ code --list-extensions --show-versions

angelomollame.conflict-squeezer@1.0.1
Angular.ng-template@14.2.0
bradlc.vscode-tailwindcss@0.8.7
dbaeumer.vscode-eslint@2.2.6
donjayamanne.githistory@0.6.19
fivethree.vscode-svelte-snippets@0.5.0
hbenl.vscode-test-explorer@2.21.1
kavod-io.vscode-jest-test-adapter@0.8.1
ms-vscode.test-adapter-converter@0.1.6
redhat.vscode-yaml@1.10.1
rvest.vs-code-prettier-eslint@5.0.4
svelte.svelte-vscode@106.1.1
wayou.vscode-todo-highlight@1.0.5
ZixuanChen.vitest-explorer@0.2.29    # <-- The plugin version

# OS / machine info
$ neofetch

             .',;::::;,'.                coo@fedora 
         .';:cccccccccccc:;,.            ---------- 
      .;cccccccccccccccccccccc;.         OS: Fedora Linux 36 (KDE Plasma) x86_64 
    .:cccccccccccccccccccccccccc:.       Host: XPS 13 9310 
  .;ccccccccccccc;.:dddl:.;ccccccc;.     Kernel: 5.19.12-200.fc36.x86_64 
 .:ccccccccccccc;OWMKOOXMWd;ccccccc:.    Uptime: 14 hours, 7 mins 
.:ccccccccccccc;KMMc;cc;xMMc:ccccccc:.   Packages: 2090 (rpm), 20 (flatpak) 
,cccccccccccccc;MMM.;cc;;WW::cccccccc,   Shell: bash 5.1.16 
:cccccccccccccc;MMM.;cccccccccccccccc:   Resolution: 1920x1200, 1920x1080 
:ccccccc;oxOOOo;MMM0OOk.;cccccccccccc:   DE: Plasma 5.25.5 
cccccc:0MMKxdd:;MMMkddc.;cccccccccccc;   WM: KWin 
ccccc:XM0';cccc;MMM.;cccccccccccccccc'   Theme: [Plasma], Adwaita [GTK2] 
ccccc;MMo;ccccc;MMW.;ccccccccccccccc;    Icons: [Plasma], Breeze-openSUSE Dark Icons [GTK2/3] 
ccccc;0MNc.ccc.xMMd:ccccccccccccccc;     Terminal: vscode 
cccccc;dNMWXXXWM0::cccccccccccccc:,      CPU: 11th Gen Intel i7-1185G7 (8) @ 4.800GHz 
cccccccc;.:odl:.;cccccccccccccc:,.       GPU: Intel TigerLake-LP GT2 [Iris Xe Graphics] 
:cccccccccccccccccccccccccccc:'.         Memory: 9404MiB / 31808MiB 
.:cccccccccccccccccccccc:;,..
  '::cccccccccccccc::;,.                                         
                                                                 
```

