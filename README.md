# Google-Android-Achitecture
谷歌的示例代码中的开发框架

https://github.com/googlesamples/android-architecture

<img src="https://github.com/googlesamples/android-architecture/wiki/images/aab-logo.png" alt="Android Architecture Blueprints"/>

### Stable samples - Java
| Sample | Description |
| ------------- | ------------- |
| [todo‑mvp](https://github.com/googlesamples/android-architecture/tree/todo-mvp/) | Demonstrates a basic [Model‑View‑Presenter](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93presenter) (MVP) architecture and provides a foundation on which the other samples are built. This sample also acts as a reference point for comparing and contrasting the other samples in this project. |
| [todo‑mvp‑clean](https://github.com/googlesamples/android-architecture/tree/todo-mvp-clean/) | Uses concepts from [Clean Architecture](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html). |
| [todo‑mvp‑dagger](https://github.com/googlesamples/android-architecture/tree/todo-mvp-dagger/) | Uses [Dagger 2](https://google.github.io/dagger/) to add support for [dependency injection](https://en.wikipedia.org/wiki/Dependency_injection). |
| [todo‑mvp‑rxjava](https://github.com/googlesamples/android-architecture/tree/todo-mvp-rxjava/) | Uses [RxJava 2](https://github.com/ReactiveX/RxJava) to implement concurrency, and abstract the data layer. |
| [todo‑mvvm‑databinding](https://github.com/googlesamples/android-architecture/tree/todo-mvvm-databinding/) | Based on the todo-databinding sample, this version incorporates the [Model‑View‑ViewModel](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93viewmodel) pattern.|
| [todo‑mvvm‑live](https://github.com/googlesamples/android-architecture/tree/todo-mvvm-live/) | Uses ViewModels and LiveData from [Architecture Components](http://developer.android.com/arch) and the Data Binding library with an MVVM architecture. |

### Stable samples - Kotlin
| Sample | Description |
| ------------- | ------------- |
| [todo-mvp-kotlin](https://github.com/googlesamples/android-architecture/tree/todo-mvp-kotlin/) | Conversion of todo-mvp to Kotlin. |
| [todo-mvvm-live-kotlin](https://github.com/googlesamples/android-architecture/tree/todo-mvvm-live-kotlin/) | Conversion of todo-mvvm-live to Kotlin. |

### External samples
[External samples](https://github.com/googlesamples/android-architecture/wiki/External-samples) are variants that may not be in sync with the rest of the branches in this repository.

| Sample | Description |
| ------------- | ------------- |
| [todo‑mvp‑fragmentless](https://github.com/Syhids/android-architecture/tree/todo-mvp-fragmentless) | Uses [View](https://developer.android.com/reference/android/view/View.html) objects instead of [Fragment](https://developer.android.com/reference/android/app/Fragment.html) objects.|
| [todo‑mvp‑conductor](https://github.com/grepx/android-architecture/tree/todo-mvp-conductor) | Uses the [Conductor](https://github.com/bluelinelabs/Conductor) framework to refactor the app to use a single Activity architecture. |
| [todo‑mvi-rxjava](https://github.com/oldergod/android-architecture/tree/todo-mvi-rxjava) | Adapts the [Model-View-Intent](https://cycle.js.org/model-view-intent.html) pattern to Android to create a fully reactive architecture. |
| [todo‑mvp-kotlin-coroutines](https://github.com/dmytrodanylyk/android-architecture/tree/todo-mvp-kotlin-coroutines) | Replaces the asynchronous operations with [Kotlin's coroutines](https://github.com/Kotlin/kotlinx.coroutines/blob/master/README.md#documentation). |


### Deprecated samples

These samples are no longer being maintained, but their implementation is still valid.

| Sample | Description |
| ------------- | ------------- |
| [todo‑mvp‑loaders](https://github.com/googlesamples/android-architecture/tree/deprecated-todo-mvp-loaders/) | Fetches data using the [Loaders API](https://developer.android.com/guide/components/loaders.html). |
| [todo‑databinding](https://github.com/googlesamples/android-architecture/tree/deprecated-todo-databinding/) | Replaced by [todo‑mvvm‑databinding](https://github.com/googlesamples/android-architecture/tree/todo-mvvm-databinding/) |
[todo‑mvp‑contentproviders](https://github.com/googlesamples/android-architecture/tree/deprecated-todo-mvp-contentproviders/) | Based on the todo-mvp-loaders sample, this version fetches data using the Loaders API, and also makes use of [content providers](https://developer.android.com/guide/topics/providers/content-providers.html). |

### Samples in progress

| Sample | Description |
| ------------- | ------------- |
| [dev‑todo‑mvvm‑rxjava](https://github.com/googlesamples/android-architecture/tree/dev-todo-mvvm-rxjava/) | Based on the todo-rxjava sample, this version incorporates the [Model‑View‑ViewModel](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93viewmodel) pattern.|

