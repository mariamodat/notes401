# Analytics backend
what is analytics ends ? 
this category of amplify enabels to collect analytics data for the app. 

we have to setup the analytics backend :

* amplify add analytics.
select the analytics provider. 

* amplify push 
here we push all the local work ino=to our backend.

* then add the dependencies 
dependencies {

    // Add these lines in `dependencies`
    implementation 'com.amplifyframework:aws-analytics-pinpoint:1.24.0'
    implementation 'com.amplifyframework:aws-auth-cognito:1.24.0'
}

* then initalize amplify analytics 
and that is done by amplify.addPlugin().


![img](https://amplify-analytics.workshop.aws/ws-overview.png)