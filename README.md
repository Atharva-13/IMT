# IMT

1-Open The zip and open the project in your preferred java IDE
2-Open applications.proprties fromm src/java/resources folder
3-And make changes to the proprties according to your DB drivers
4-run the java application
5-make sure your db service is running
6-open postman and use http://localhost:{port numbber (9090 in app.properties) if you made changes}/api/{clients/policies/claims}
7-http://localhost:9090/api/clients   |  http://localhost:9090/api/policies  | http://localhost:9090/api/claims
8-test out GET POST PUT DELETE...
9-client data syntax


{ 
    "name": "Atharvaa",
    "dob": "1990-01-01",
    "address": "123 St",
    "contactInformation": "9538572803",
    "policies": [
        {
            "policyNumber": null,
            "type": null,
            "coverageAmount": null,
            "premium": null,
            "startDate": null,
            "endDate": null,
            "client": null,
            "claims": null
        }
    ]
}


10-policy syn
{
    "policyNumber": "100",
    "type": "Health",
    "coverageAmount": 200000,
    "premium": 1300,
    "startDate": "1990-01-01",
    "endDate": "2022-01-01",
    "client": null,
    "claims": null
}

11-claim

{
    "id": 1,
    "claimNumber": "1407141",
    "description": "Accident",
    "claimDate": "2022-09-01",
    "claimStatus": "Claimed",
    "policy": null
}


Thank you!!
