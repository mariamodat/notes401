# Amazon Cognito 
what is amazon cognito ?
cognito is a web service that delivers scoped temporary credentials to mobile devices and other untrusted environments.


## Authentication 
it's a built-in support with a amazon cognito user pool, used to provide authentication for the users and gives authorizations.

![img](https://cdn-ssl-devio-img.classmethod.jp/wp-content/uploads/2014/09/cognito-developer-identity.png)

## Getting started
using the CLI 
* `amplify add auth`
* `amplify push`
**Notice that amplifyconfiguration.json file must be updated to have the authentication properties. 


## Dependencies 
dependencies {
    `implementation 'com.amplifyframework:aws-auth-cognito:1.24.0'`
}