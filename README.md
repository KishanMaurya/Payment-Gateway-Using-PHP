# Payment-Gateway-Using-PHP
Instamozo -PaymentGateway-PHP (PHP , Bootstrap 4+ , Css , HTML-5 , Jquery)


Assists you to programmatically create, edit and delete Links on Instamojo in PHP
![home](https://user-images.githubusercontent.com/45098599/79463263-3b416a00-8016-11ea-89eb-a05cc308f9a9.png)
![fill](https://user-images.githubusercontent.com/45098599/79463273-3ed4f100-8016-11ea-8770-0baf02b7534e.png)
![fill-card-details](https://user-images.githubusercontent.com/45098599/79463331-5613de80-8016-11ea-8efa-036630acdc25.png)
![instamozo](https://user-images.githubusercontent.com/45098599/79463348-5b712900-8016-11ea-95ca-6c0b38377089.png)
![enter security-pin](https://user-images.githubusercontent.com/45098599/79463372-6330cd80-8016-11ea-8c39-5049637e5dd9.png)
![thank-you-page](https://user-images.githubusercontent.com/45098599/79463383-67f58180-8016-11ea-8de0-2cfb0c7f4136.png)

![Payment Gateway GIF-downsized](https://user-images.githubusercontent.com/45098599/79464303-8a3bcf00-8017-11ea-916a-49905128caaa.gif)


.

Note: If you're using this wrapper with our sandbox environment https://test.instamojo.com/ then you should pass 'https://test.instamojo.com/api/1.1/' as third argument to the Instamojo class while initializing it. API key and Auth token for the same can be obtained from https://test.instamojo.com/developers/ (Details: Test Or Sandbox Account).

$api = new Instamojo\Instamojo(API_KEY, AUTH_TOKEN, 'https://test.instamojo.com/api/1.1/');
