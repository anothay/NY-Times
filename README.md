# [Model-View-ViewModel (MVVM)](https://github.com/ebnrdwan/NY-Times.git)

 [![kotlin](https://img.shields.io/badge/Kotlin-1.3.xxx-brightgreen.svg)](https://kotlinlang.org/)  [![Mockito](https://img.shields.io/badge/Mockito-testing-yellow.svg)](https://site.mockito.org/)      [![Junit4](https://img.shields.io/badge/Junit4-testing-yellowgreen.svg)](https://junit.org/junit4/)   [![Espresso](https://img.shields.io/badge/Espresso-testing-lightgrey.svg)](https://developer.android.com/training/testing/espresso/)  [![Dagger 2](https://img.shields.io/badge/Dagger-2.xx-orange.svg)](https://google.github.io/dagger/)  [![Kotlin-Android-Extensions ](https://img.shields.io/badge/Kotlin--Android--Extensions-plugin-red.svg)](https://kotlinlang.org/docs/tutorials/android-plugin.html) [![MVVM ](https://img.shields.io/badge/Clean--Code-MVVM-brightgreen.svg)](https://github.com/googlesamples/android-architecture) 
  
![MVVM3](https://user-images.githubusercontent.com/1812129/68319232-446cf900-00be-11ea-92cf-cad817b2af2c.png)



**MVVM Best Pratice:**
- Avoid references to Views in ViewModels.
- Instead of pushing data to the UI, let the UI observe changes to it.
- Distribute responsibilities, add a domain layer if needed.
- Add a data repository as the single-point entry to your data.
- Expose information about the state of your data using a wrapper or another LiveData.
- Consider edge cases, leaks and how long-running operations can affect the instances in your architecture.
- Don’t put logic in the ViewModel that is critical to saving clean state or related to data. Any call you make from a ViewModel can be the last one.

## Goal
Build an open source math, memory and focus improvement app. The app itself consists of a bunch of small games. Right now I try to keep the games as simple as possible to allow the implementation for the terminal client.

## Doing
- adding more ui testing and validate the fleaky ones
- adding integration test
- apply custom lint rules
- revisit architecture and  testing and for upcoming enhancements


## Todo
**apply static code analysis: apply one or more**
- detekt
- findBug
- SonarQube

**using CI/CD: apply one or more**
- Gitlab with integration with slack
- Travis




## Contribution
Very welcome.



## Technical Stacks:

* [x] MVVM Presentation Architecture
* [x] Unit tests using Junit    
* [x] UI tests using espresso
* [x] Modular Clean Architecture



 ### Tools & Dependencies: ###
 
- [kotlin](https://kotlinlang.org/)
- [kotlinDsl](https://kotlinlang.org/)
- [RxJava2](https://github.com/ReactiveX/RxJava)
- [RxKotlin](https://github.com/ReactiveX/RxJava)
- [RxAndroid](https://github.com/ReactiveX/RxAndroid)
- [Retrofit2](https://github.com/square/retrofit)
- [Dagger2](https://dagger.dev//)
- [Android Navigation Component](https://developer.android.com/guide/navigation/navigation-getting-started)
- [Android Jetpack](https://developer.android.com/jetpack/docs/getting-started)
- [Picasso](https://github.com/square/picasso)
- [OkHttp](https://github.com/square/okhttp)
- [Junit4](https://junit.org/junit4/)
- [Espresso](https://dagger.dev//)
- [Mockito](https://mockito.io//)
- [Fragment Test](https://developer.android.com)







## Code Coverage

coverage reports can be generated by executing the following command in terminal `gradlew createDebugCoverageReport`
it will be generated at `app\build\reports\coverage\debug\index.html`




## Lint Result
lint check reports can be generated by executing the following command in terminal `gradlew app:lintDevelopmentdebug`

  

    

## LICENSE
Copyright [2020] [Ebnrdwan]    
Licensed under the Apache License, Version 2.0 (the "License");    
you may not use this file except in compliance with the License.    
You may obtain a copy of the License at    
    
 http://www.apache.org/licenses/LICENSE-2.0    
Unless required by applicable law or agreed to in writing, software    
distributed under the License is distributed on an "AS IS" BASIS,    
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.    
See the License for the specific language governing permissions and    
limitations under the License.
