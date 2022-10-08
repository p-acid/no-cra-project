# CRA 없이 React 프로젝트 구성

- `react`
- `typescript`
- `babel`
- `webpack`
- `yarn`

## 기본 구성

```sh
# 폴더 생성
mkdir no-cra-react
```

### 기본 디렉토리 구조

```
- src
  └ App.tsx
  └ index.tsx
- public
  └ index.html
```

## React

```sh
yarn init
yarn add react react-dom
```

## Typescript

```sh
# typescript 및 타입 파일
yarn add -D typescript @types/react @types/react-dom
tsc --init
```

### 파일 작성

- `tsconfig.json`

## Babel

```sh
# babel 설정
yarn add -D babel-loader @babel/core @babel/preset-env @babel/preset-react @babel/preset-typescript
```

### 파일 작성

- `babel.config.js`

## Webpack

```sh
# webpack 설정
yarn add -D webpack webpack-cli webpack-dev-server webpack-merge html-webpack-plugin ts-loader
```

### 파일 작성

- `webpack.common.js`
- `webpack.dev.js`
- `webpack.prod.js`
