# Closure-dependency-management



This project is used to showcase on how to manage the dependencies in cleaner way than just implementing straightaway


step 1: copy paste the " *dependencies.gradle* " into your project

step 2: import the gradle as plugin into your app.gradle like " *apply from: "${project.rootDir}/dependencies.gradle"* "

step 3: declare the dependency like function call in your "*app.gradle*" like below


                  dependencies {

                      AndroidSupport()
                      Retrofit()
                      Koin()
                      Glide()
                      FacebookDebugger()
                      ReactiveX()
                      encryptedPrefs()
                      Room()

                  }

step 4: voila you have sucessfully cleaned your dependencies
