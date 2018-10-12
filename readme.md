### 使用 & Usage

`npm i vue-simple-progressbar -S`

`import vpr from 'vue-simple-progressbar'`
`Vue.use(vpr)`

`Vue.$progress.start()`
`Vue.$progress.finish()`
`Vue.$progress.error()`
`Vue.$progress.success()`
`Vue.$progress.warning()`

#### Or through component instance

`this.$progress.{method}()`