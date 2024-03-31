There is the little snippet for consuming Teamcenter services via REST API within this repository.
You should use Postman >= 9.15.2

There are variables at the collection level for configuring that snippet
![Configuring](https://user-images.githubusercontent.com/44873126/163731120-0eac3b40-5ddc-41e2-9c0e-520b5ba45b41.png)

There are several HTML widgets for visualizing response from Teamcenter services, like that

![GetINBOX](https://user-images.githubusercontent.com/44873126/163731321-62bdc7d7-ac19-4f0f-8ac9-01321334c26a.png)

![GetQuery](https://user-images.githubusercontent.com/44873126/163731326-ac51a8e8-e5dd-4bb7-b1c7-1ec4dd18ca4b.png)


**How to get the Teamcenter API description**

 - cd ...aws2\stage 
 - initenv 
 - npm run genSoaApi 
 - cd ...aws2\stage\out\soa\api
