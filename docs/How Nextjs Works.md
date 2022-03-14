### Where your code runs: Development vs Production

- development stage 👉🏻 developer experience 향상에 기여 (e.g. TS, ESLint integration, Fast Refresh etc.)
- production stage 👉🏻 end-user experience 향상에 기여

From development to production, 그 사이에 코드는 1) compiled, 2) bundled, 3) minified, 4) code split 과정을 거친다

#### Compilation

> the process of taking code in one language and outputting it in another language or another version of that language.

Next.js에서 compilation은 development stage에서 진행된다. Compilation은 development에서 production으로 가는 준비과정이다.

#### Minifying

> the process of removing unnecessary code formatting and comments without changing the code’s functionality

Next.js에서 JS와 CSS 파일들은 production을 위해 자동적으로 minified 된다.

#### Bundling

> the process of resolving the web of dependencies and merging (or ‘packaging’) the files (or modules) into optimized bundles for the browser, with the goal of reducing the number of requests for files when a user visits a web page.

### When your code runs: Build Time vs Runtime

### Where rendering happens: Client vs Server
