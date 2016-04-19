# KangarooIMG
Javascript framework to create bouncing images on your website, quickly and easily.


Demo:
--------------


Setup:
--------------
First you need to implement the javascript and css files into your code. Add this to your code:

	<link href="kangarooimg.css" rel="stylesheet" type="text/css">
	<script src="kangarooimg.js"></script>

Next, you use javascript to call the one and only class in the framework, named Kangaroo. Add this to a variable to start preparing your first Kangaroo and give it a name and a ID name for the div it should be put in (This div will be added into the body by default). Like so:

	var kangaroo1 = new Kangaroo('Patrick', 'KangarooHuis');

**Kangaroo Class**

| **Parameters** | **Type** | **Default Value** | **Description** |
| -------------- | -------- | ----------------- | --------------- |
|   *firstName*  | String   |                   |                 |
|   *divName*    | String   |                   |                 |
|  *parentName*  | String   |                   |                 |

Methods:
--------------
