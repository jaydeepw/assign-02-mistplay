# Mistplay
A simple app to showcase MVVM with paging and search functionality

# Assumptions and deliberations
- The app being a simple search catalogue, I have not used [Fragments](https://developer.android.com/guide/components/fragments)
but implemented the functionality within the activity itself


# Application architecture and technical details
- This app uses MVVM as the software development pattern
- Uses Kotlin as the programming language
- Uses Retrofit for retrieving data from the webservice
- Uses Repository Pattern for transparent access of data to the view layer
- Adheres to software design principles like
    - Separation of Concerns
    - DRY(Do not repeat yourself)
    - Dependency Injection