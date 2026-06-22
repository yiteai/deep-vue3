# Deep Vue 3: From History to Engine Internals

> Not a Vue 3 tutorial — a Vue 3 internals book. From Evan You's three rewrite decisions to the complete internal mechanics of the Proxy reactivity engine, template compiler, and Diff algorithm. Four-layer structure per chapter serves developers at every level: Level 1 direct conclusions, Level 2 engine internals, Level 3 Vue 3 source code and design docs, Level 4 high-frequency pitfalls. 32 chapters covering history, reactivity, compilation, renderer, Composition API, state/routing, animation/errors/security, and performance engineering.

**📖 Read the full book online (free): [https://tools.yiteai.com/en/books/vue3](https://tools.yiteai.com/en/books/vue3)**

*A deep-dive technical book by [YiteAI](https://tools.yiteai.com). This repo is the companion index — every chapter links to the full text on the site.*

---
## Table of Contents

- [Three Rewrites of Vue: From Angular Directives to Proxy Reactivity](https://tools.yiteai.com/en/books/vue3/ch01)
- [Birth of Composition API: RFC 0013, the Mixin Disaster and Community Debate](https://tools.yiteai.com/en/books/vue3/ch02)
- [Vue 3 Design Philosophy: Tree-shakable Architecture, Cross-Platform Renderer, Type-First](https://tools.yiteai.com/en/books/vue3/ch03)
- [Proxy and Reflect: Complete Semantics of 13 Traps and Reactive Infrastructure](https://tools.yiteai.com/en/books/vue3/ch04)
- [effect, track, trigger: The Complete Dependency Tracking Engine of Vue 3](https://tools.yiteai.com/en/books/vue3/ch05)
- [ref and reactive: Internal Differences, Auto-Unwrapping Boundaries and Selection Guide](https://tools.yiteai.com/en/books/vue3/ch06)
- [computed: Lazy Evaluation, Caching Mechanism and Circular Dependency Handling](https://tools.yiteai.com/en/books/vue3/ch07)
- [watch and Scheduler: Async Update Queue, Flush Strategy and Race Condition Cleanup](https://tools.yiteai.com/en/books/vue3/ch08)
- [effectScope, customRef, triggerRef: Design Intent Behind Advanced Reactivity APIs](https://tools.yiteai.com/en/books/vue3/ch09)
- [Full Compilation Pipeline: parse, transform, codegen End-to-End](https://tools.yiteai.com/en/books/vue3/ch10)
- [Static Hoisting and PatchFlag: How Compile-Time Performance Hints Work](https://tools.yiteai.com/en/books/vue3/ch11)
- [Block Tree: Dynamic Node Tracking and Targeted Diff Design](https://tools.yiteai.com/en/books/vue3/ch12)
- [v-model, v-for and Custom Directives: Compilation Output and Runtime Handling](https://tools.yiteai.com/en/books/vue3/ch13)
- [VNode Internals and ShapeFlags Bitwise Operations](https://tools.yiteai.com/en/books/vue3/ch14)
- [Diff Algorithm: LIS Step-by-Step Derivation and the Dual Role of key](https://tools.yiteai.com/en/books/vue3/ch15)
- [Component Mount and Update: Complete mountComponent to patch Execution Chain](https://tools.yiteai.com/en/books/vue3/ch16)
- [Async Components, Suspense, Teleport and KeepAlive: Implementation Internals](https://tools.yiteai.com/en/books/vue3/ch17)
- [Cross-Platform Renderer: Design Philosophy and Implementation of Custom Renderers](https://tools.yiteai.com/en/books/vue3/ch18)
- [setup() Execution Context: Call Timing, getCurrentInstance and Lifecycle Registration](https://tools.yiteai.com/en/books/vue3/ch19)
- [provide/inject: Cross-Level Dependency Injection Lookup Chain and Type Safety](https://tools.yiteai.com/en/books/vue3/ch20)
- [Composables Design: State Ownership, Side Effect Cleanup and Common Pitfalls](https://tools.yiteai.com/en/books/vue3/ch21)
- [script setup Compilation: Macro Expansion, Top-Level Binding Exposure and Constraints](https://tools.yiteai.com/en/books/vue3/ch22)
- [Pinia Source Analysis: defineStore Internals and Reactive Store Creation](https://tools.yiteai.com/en/books/vue3/ch23)
- [Vue Router 4: Route Matching Algorithm and Async Navigation Guard Pipeline](https://tools.yiteai.com/en/books/vue3/ch24)
- [TypeScript Integration: Generic Compiler Macros, Type Inference Chain and Engineering Type System](https://tools.yiteai.com/en/books/vue3/ch25)
- [Form Handling: v-model Compilation, Validation Patterns and VeeValidate Internals](https://tools.yiteai.com/en/books/vue3/ch26)
- [Transition Animation System: CSS Class State Machine, JS Hooks and FLIP Principle](https://tools.yiteai.com/en/books/vue3/ch27)
- [Error Boundaries and Global Error Handling: onErrorCaptured Propagation and Monitoring](https://tools.yiteai.com/en/books/vue3/ch28)
- [Security: v-html XSS Attack Surface, Template Injection and CSP Defense](https://tools.yiteai.com/en/books/vue3/ch29)
- [Rendering Performance: Virtual Lists, v-memo, shallowRef and Memory Leak Detection](https://tools.yiteai.com/en/books/vue3/ch30)
- [Bundle and Loading Performance: Tree-shaking, Code Splitting and Preloading](https://tools.yiteai.com/en/books/vue3/ch31)
- [SSR, Nuxt 3 and Production: Hydration, Caching Strategy and CI/CD Pipeline](https://tools.yiteai.com/en/books/vue3/ch32)

---
## 中文版

# Vue 的三次重写：从 Angular 指令到 Proxy 响应式的演进史

**📖 在线免费阅读全文:[https://tools.yiteai.com/books/vue3](https://tools.yiteai.com/books/vue3)**

### 目录

- [Vue 的三次重写：从 Angular 指令到 Proxy 响应式的演进史](https://tools.yiteai.com/books/vue3/ch01)
- [Composition API 的诞生：RFC 0013、Mixin 灾难与社区博弈](https://tools.yiteai.com/books/vue3/ch02)
- [Vue 3 设计哲学：Tree-shakable 架构、跨平台渲染器与类型优先](https://tools.yiteai.com/books/vue3/ch03)
- [Proxy 与 Reflect：13 种 trap 的完整语义与响应式基础设施](https://tools.yiteai.com/books/vue3/ch04)
- [effect、track、trigger：Vue 3 依赖追踪引擎的完整机制](https://tools.yiteai.com/books/vue3/ch05)
- [ref 与 reactive：两套 API 的内部差异、自动解包边界与选择准则](https://tools.yiteai.com/books/vue3/ch06)
- [computed：懒求值、缓存机制与循环依赖的处理策略](https://tools.yiteai.com/books/vue3/ch07)
- [watch 与调度器：异步更新队列、flush 策略与竞态清理](https://tools.yiteai.com/books/vue3/ch08)
- [effectScope、customRef、triggerRef：响应式系统进阶 API 的设计意图](https://tools.yiteai.com/books/vue3/ch09)
- [编译管道全链路：parse → transform → codegen 的完整过程](https://tools.yiteai.com/books/vue3/ch10)
- [静态提升与 PatchFlag：编译期性能标注的原理与效果](https://tools.yiteai.com/books/vue3/ch11)
- [Block Tree：动态节点追踪与靶向 diff 的设计](https://tools.yiteai.com/books/vue3/ch12)
- [v-model、v-for、自定义指令的编译展开与运行时处理](https://tools.yiteai.com/books/vue3/ch13)
- [VNode 内部结构与 ShapeFlags 位运算](https://tools.yiteai.com/books/vue3/ch14)
- [Diff 算法：最长递增子序列手推过程与 key 的双重作用](https://tools.yiteai.com/books/vue3/ch15)
- [组件挂载与更新：mountComponent → patch 的完整执行链路](https://tools.yiteai.com/books/vue3/ch16)
- [异步组件、Suspense、Teleport 与 KeepAlive 的实现机制](https://tools.yiteai.com/books/vue3/ch17)
- [跨平台渲染器：自定义渲染器的设计哲学与实现](https://tools.yiteai.com/books/vue3/ch18)
- [setup() 执行上下文：调用时机、getCurrentInstance 与生命周期注册](https://tools.yiteai.com/books/vue3/ch19)
- [provide/inject：跨层级依赖注入的查找链与类型安全实践](https://tools.yiteai.com/books/vue3/ch20)
- [Composables 设计哲学：状态所有权、副作用清理与高频易错陷阱](https://tools.yiteai.com/books/vue3/ch21)
- [<script setup> 编译转换：宏展开、顶层绑定暴露与限制](https://tools.yiteai.com/books/vue3/ch22)
- [Pinia 源码解析：defineStore 内部机制与响应式 store 的创建](https://tools.yiteai.com/books/vue3/ch23)
- [Vue Router 4：路由匹配算法与导航守卫的异步流水线](https://tools.yiteai.com/books/vue3/ch24)
- [TypeScript 集成：泛型编译宏、类型推断链与工程化类型体系](https://tools.yiteai.com/books/vue3/ch25)
- [表单处理：v-model 编译展开、校验设计模式与 VeeValidate 原理](https://tools.yiteai.com/books/vue3/ch26)
- [Transition 动画系统：CSS 类名状态机、JS 钩子与 FLIP 原理](https://tools.yiteai.com/books/vue3/ch27)
- [错误边界与全局错误处理：onErrorCaptured 传播链与监控接入](https://tools.yiteai.com/books/vue3/ch28)
- [安全：v-html XSS 攻击面、模板注入与 CSP 防御策略](https://tools.yiteai.com/books/vue3/ch29)
- [渲染性能：虚拟列表、v-memo、shallowRef 与内存泄漏排查](https://tools.yiteai.com/books/vue3/ch30)
- [包体积与加载性能：Tree-shaking 机制、代码分割与预加载策略](https://tools.yiteai.com/books/vue3/ch31)
- [SSR、Nuxt 3 与生产部署：水合机制、缓存策略与 CI/CD 流水线](https://tools.yiteai.com/books/vue3/ch32)

---
## About YiteAI

[YiteAI](https://tools.yiteai.com) 是面向开发者的 AI 工具箱 + 技术书库 + AI Agent Skills 市场。更多免费技术书:[https://tools.yiteai.com/books](https://tools.yiteai.com/books)

> ⚖️ Content © YiteAI. This repo indexes the book; the full text is hosted on the site. Please link back rather than mirror.
