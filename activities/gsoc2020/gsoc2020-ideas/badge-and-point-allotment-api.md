# Badge and point allotment API inside Codebadge

### Priority:

High

### Description:

In Codebadge, presently all the badge allotment computation are taking place at browser level. We require to shift all the badge related computation at back-end using nodejs API. The task to be preformed under this task are:-

* Designing a database schema to manage user points for projects and organization, storing badge templates in efficient manner, storing admin defined pattern for awarding badges and special badges.
* Design a badge allotment API which shall fulfill following criteria's:-
  * Admin can decide the count of points for allotting points.
  * Using Machine Learning allocating points as per past relocatable issues.
  * Designing a special badge allotment system which can be decided by the admin while creating an account.
* Designing an API system which returns render-able badges. Badges must be saved in minified format which shall be improved in quality and size on rendering time.
* Creating shareable illustrator system which admin can only share with his organization contributors using email/github username.
* Fetching contribution outside browser without using crone jobs approach which makes the computation speed slower.

{% hint style="warning" %}
**References:** [**Trello Webhooks**](https://developers.trello.com/page/webhooks) **,** [**Playing with Github Webhooks \| Github**](https://developer.github.com/webhooks/)\*\*\*\*
{% endhint %}

### **Required Skills/knowledge:**

* Good knowledge of databases
* languages such as NodeJs
* experience of working sockets programming and using github apis
* Good Knowledge of Modules Bundling

### Difficulty Level:

Moderate

### Expected Outcome:

This project would result in the improvement in the badge alotment system of Codebadge project which will allow admin to judge the progress of the project in the better way.

### Potential Mentors:

[**Jaskirat Singh**](https://github.com/jaskirat2000) and [**Vaibhav D. Aren**](https://github.com/vaibhavdaren)

