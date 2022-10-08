# CRA 없이 React 프로젝트 구성

- `yarn` + `react`

## 기본 구성

```sh
# 폴더 생성
mkdir no-cra-react
```

```sh
# react 설정
yarn init
yarn add react react-dom
```

```sh
# typescript 및 타입 파일
yarn add -D typescript @types/react @types/react-dom
tsc --init
```

```sh
# babel 설정
yarn add -D babel-loader @babel/core @babel/preset-env @babel/preset-react @babel/preset-typescript
```

```sh
# webpack 설정
yarn add -D webpack webpack-cli webpack-dev-server webpack-merge html-webpack-plugin ts-loader
```
