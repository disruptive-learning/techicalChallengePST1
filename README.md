![](https://gigstack.pro/images/gigstack-pro.png)

### About Gigstack

Management and **automation** software for electronic invoicing for Mexican startups and companies, which reduces up to 90% of the time for administrative tasks.

### Technical challenge for Full-Stack Developers.

#### Why:

The goal for this technical challenge is to prove the ability to work with our stack. There's no right answer. Please feel free to propose new ways to complete the challenge.

#### Requirements:

*   Use ant.design to design the components.
*   We use firebase functions for our server. Please create functions in the required format (no need to deploy), and use http.onRequest and authenticate with token (very important to show how you are authenticating the request).
*   Follow [atomic design](https://bradfrost.com/blog/post/atomic-web-design/) pattern.
*   Use FirebaseFirestore to store data.
*   Use FirebaseAuth to authenticate a user.
*   Use React Hooks

#### The case:

Imagine the next scenario:

We need to create a new integration for our user, so we need to give the ability for the user to configure the settings in their account. These settings require you to have 2 inputs:

*   Email
*   API Key

After saving, the user needs to have immediate feedback that the integration is connected and no more actions are needed. (we are not deploying the server, please make direct update to the db)

Once the user has all the settings up, the cloud function (no need to deploy) needs to handle some external API calls. You can choose one that requires authentication with api key or feel free to use [https://github.com/open-pay/openpay-node](https://github.com/open-pay/openpay-node) (no need to create an account) to retrieve all payments (openpay.charges) from the user account using the API key configured before in the account.  
 

#### Instructions

*   Download or fork the code
*   Deliver in a .zip file or access to a github repo.

#### Goal:
 
*   Create a settings page - 
*   Show realtime updates for the user information in settings page (we are not deploying the server, so please make a un update to the user db and show the update in the UI in real time) - 
*   Show a PopUp to add the required configuration - 
*   Show the index.js file with the cloud function(s) (no need to deploy) -
*   Document your code (very important) -

#### Resources:

[https://ant.design/](https://ant.design/)

[https://firebase.google.com/](https://firebase.google.com/)

*   [https://firebase.google.com/docs/functions](https://firebase.google.com/docs/functions)
*   [https://firebase.google.com/docs/firestore](https://firebase.google.com/docs/firestore)

[https://github.com/FirebaseExtended/reactfire](https://github.com/FirebaseExtended/reactfire)

[https://bradfrost.com/blog/post/atomic-web-design/](https://bradfrost.com/blog/post/atomic-web-design/)

[https://gigstack.pro](https://gigstack.pro)
