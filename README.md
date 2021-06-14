# storybook-repro-15228
Reproduction for storybook issue https://github.com/storybookjs/storybook/issues/15228

## Reproduce Steps

1. - [ ] `git clone https://github.com/Asim-Tahir/storybook-repro-15228.git`
2. - [ ] `yarn storybook`
3. - [ ] Go to http://localhost:6006 
4. - [ ] Open devtools
5. - [ ] Change between `canvas` and `docs` tab or change selected story.
6. - [ ] Appears white border.

## System
```
System:
    OS: Windows 10 10.0.21390
    CPU: (8) x64 Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz
  Binaries:
    Node: 16.2.0 - C:\Program Files\nodejs\node.EXE
    Yarn: 1.22.10 - C:\Program Files\nodejs\yarn.CMD
    npm: 7.14.0 - C:\Program Files\nodejs\npm.CMD
  Browsers:
    Edge: Spartan (44.21390.1.0), Chromium (91.0.864.48)
  npmPackages:
    @storybook/addon-actions: ^6.3.0-rc.4 => 6.3.0-rc.4
    @storybook/addon-essentials: ^6.3.0-rc.4 => 6.3.0-rc.4
    @storybook/addon-links: ^6.3.0-rc.4 => 6.3.0-rc.4
    @storybook/react: ^6.3.0-rc.4 => 6.3.0-rc.4
```

## Additional context
![Screenshot 2021-06-14 110328](https://user-images.githubusercontent.com/29407019/121866266-6fdaaf80-cd07-11eb-9187-886d3c95694f.png)
