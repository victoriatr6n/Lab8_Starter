# Lab8-Starter

Victoria Tran

[Link to GitHub Page](https://victoriatr6n.github.io/Lab8_Starter/)

How are graceful degradation and service workers related?
Service workers are related to graceful degradation since they allow the webpage to still work/load offline. In the same way, with graceful degradation, we start with the more advanced technology and then enhance and worry about the low level issues (which aren't required but enhance the website). The issue of a webpage working when the user is offline is a low level issue that we use ServiceWorkers to address once the main functionality of the page has been developed. Graceful degradation scales the website after the core functionality has been implemented, for example, in the cases in which the browser the user is old, or other cases where the system/environment the user is in is not the most ideal for the website to run in. It makes sure the website still works in these cases (even if it is not the most optimal performance). The ServiceWorkers make sure that even if the user is offline, if there is data cached, the website can still function, which is this sort of "edge case" that we are considering after the website is mainly implemented.

<img width="1210" alt="pwa" src="https://github.com/user-attachments/assets/ef144efe-aea9-4d53-97cb-ae246d7a0591" />
