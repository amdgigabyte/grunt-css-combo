# grunt-css-combo

[CSS Combo](https://github.com/daxingplay/css-combo)���ߵ�[grunt](https://github.com/gruntjs/grunt)���

## ��ο�ʼ
���ն���`cd`�������ĿĿ¼�����`grunt.js`����Ŀ¼����Ȼ��ʹ��`npm install grunt-css-combo`����װ���

Ȼ������������ļ� `grunt.js` ������ò��:

```js
grunt.loadNpmTasks('grunt-css-combo');
```

## �ĵ�

ʹ�úܼ򵥣�ֱ����CSS Combo�����ü��ɡ����Խ�����ֱ���Ʋ�CSS Combo���ĵ�[KSP](https://github.com/daxingplay/css-combo)���ĵ�.

```js
grunt.initConfig({

    'css-combo':{
        file1:{
            'target': 'xxx.source.css',
            'output': 'xxx.css',
            'inputEncoding': 'utf-8',
            'outputEncoding': 'gbk',
            'compress': true,
            'debug': false
        },

        file2: {
            ...
        }
    }
});
```
Ȼ�����ǿ��Ա����ͨ��grunt������ִ��

```bash
$ grunt css-combo
```
����ִ�����е���
```bash
$ grunt css-combo:file1
```

## License
Copyright (c) 2012 daxingplay
Licensed under the MIT license.