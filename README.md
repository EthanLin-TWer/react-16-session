# React 16.x new features

大 feature 及其 timeline

- (16.0) `Fragments`
- (16.0) `ErrorBoundary`
- (16.0) `Portal`
- (16.3) `Context` API
- (16.3) Lifecycle Methods
- (16.6) `React.memo`
- (16.6) `React.lazy` & `React.Suspence`
- (16.x/Q1 2019) Hooks
- (16.x/Q1 2019) Suspense (for data fetching)

展开思路：

- 是个啥
- 解决了什么问题
- 采用建议
- 迁移建议
- 代码片段

## 16.0

- [x] fragments & strings: no need for a wrapping component
- [x] error boundary
- [ ] portal: https://reactjs.org/docs/portals.html - cannot understand
- [ ] dom attributes - 这是个很细节的东西。用到再看就好了
  - https://reactjs.org/blog/2017/09/08/dom-attributes-in-react-16.html
- [ ] architecture rewrite: https://code.fb.com/web/react-16-a-look-inside-an-api-compatible-rewrite-of-our-frontend-ui-library/

### Dom Attributes

- 是个啥：React 15 以前你在 html 里写 React 不认识的属性是会被直接忽略的
- 解决了什么问题：现在可以写了
- 采用建议：
- 迁移建议
- 代码片段

## 16.3

- [x] `Context` API - 还是不错的东西
  - [ ] https://reactjs.org/docs/context.html
  - [x] https://www.zhihu.com/question/267168180/answer/319754359
- lifecycle changes:
  - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html
  - https://reactjs.org/blog/2018/06/07/you-probably-dont-need-derived-state.html
  - [x] https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#fetching-external-data-when-props-change
- `StrictMode`: https://reactjs.org/docs/strict-mode.html
- async rendering:
  - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html
  - https://t.co/3snoahB3uV
  - pic.twitter.com/egQ988gBjR
- refs support:

  - https://reactjs.org/docs/refs-and-the-dom.html
  - https://reactjs.org/docs/forwarding-refs.html

## 16.4

- Pointer events: https://reactjs.org/blog/2018/05/23/react-v-16-4.html

## 16.5

- profiler: https://reactjs.org/blog/2018/09/10/introducing-the-react-profiler.html

## 16.6

- `React.memo`: `PureComponent` for functional components
- `React.lazy` & `React.suspence`(data fetching with Apollo):
  - https://reactjs.org/docs/code-splitting.html#reactlazy
  - https://medium.com/@pomber/lazy-loading-and-preloading-components-in-react-16-6-804de091c82d
- `contextType`

## Roadmap

https://reactjs.org/blog/2018/11/27/react-16-roadmap.html

- React 16.6 with Suspense for Code Splitting (already shipped)
- A minor 16.x release with React Hooks (~Q1 2019)
- A minor 16.x release with Concurrent Mode (~Q2 2019)
- A minor 16.x release with Suspense for Data Fetching (~mid 2019)

2019 plans:

- Modernizing React DOM: https://reactjs.org/blog/2018/11/27/react-16-roadmap.html#modernizing-react-dom
- Suspense for Server Rendering: https://reactjs.org/blog/2018/11/27/react-16-roadmap.html#suspense-for-server-rendering

## Todo

- https://reactjs.org/blog/2018/11/13/react-conf-recap.html
- https://www.youtube.com/watch?v=nLF0n9SACd4
