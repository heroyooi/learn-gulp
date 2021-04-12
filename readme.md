# Learn Gulp

Learn Gulp by building an awesome development environment

```command
npm i gulp-cli -g
npm init
npm i gulp -D
npm i @babel/register @babel/core @babel/preset-env -D
```

## Gulp + Babel

```.babelrc
{
  "presets": ["@babel/preset-env"]
}
```

## plugin

```command
npm i del
npm i gulp-pug gulp-image -D
npm i node-sass gulp-sass -D
```

- del: 잘못 빌드되었을 경우 기존의 빌드를 지우고 다시 빌드 되도록 하는 모듈

## Dev Server

```command
npm i gulp-webserver -D
```

## Minify + Autoprefixer

```command
npm i gulp-autoprefixer gulp-csso
```

## Babelify + Browserify

```command
npm i gulp-bro babelify uglifyify -D
```

- Browserify는 개발자들이 브라우저에서 Node.js 스타일의 모듈을 사용하기 위한 오픈 소스 JS 툴이다.
  - 기본적으로 브라우저는 import, export 같은 문법을 이해하지 못한다. Browserify는 이런걸 이해할 수 있도록 도와준다.
  - browserify를 import 하고, browserify 안에서 babel을 실행시켜야한다.

## Deploying to GH Pages

```command
npm i gulp-gh-pages -D
```

## 참고 url

[gulp 공식문서](https://gulpjs.com/)
[gulp 플러그인 | gulp-webserver](https://www.npmjs.com/package/gulp-webserver)
[gulp 플러그인 | gulp-image](https://www.npmjs.com/package/gulp-image)
[배포 url](http://heroyooi.github.io/learn-gulp)

## 강좌

[Gulp 90분 마스터하기](https://nomadcoders.co/gulp-for-beginners/lectures/1635)
