Jia Yu (Johnny) Zou \
This repo is a clone of: https://github.com/miguelgrinberg/flasky

Activity 1: \
![Screenshot Activity 1](./Screenshots/Activity1.PNG?raw=true "Activity 1")

Activity 2: \
![Screenshot Activity 2](./Screenshots/Activity2.PNG?raw=true "Activity 2")

Activity 3: \
<strong>Briefly summarize what are the Flask context globals.</strong> \
Flask context globals allow different variables to be globally accessible to a thread without interfering with other threads. The two contexts in Flask are the application context and the request context which allows the pair of variables current_app, g and request, session to be available respectively. Before handing a request, Flask makes these variables available to the thread and after the request is handled, these context variables are removed.