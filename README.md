# Durbin_Technlogy_Assignment
Task for Backend Developer

Develop a simple backend api through which an user can perform the following operations

Upload single / multiple documents (PDF/DOCX)
Parse the resume fields as mentioned below
Name, Phone No, Email ID, Address
Work Experience
Education
Certifications
Skills
For the single document upload the response should be
{
    "response": {
    "name": " Aaron Engenito",
    "phone": "+1 607 422 5918",
    "address": " Castle Creek NY",
    "email": "ajengenito@gmail.com",
    "experience": [
      {
      "company": "Dedicated logistics partners - Binghamton, NY",
      "position": "Delivery Driver",
      "timeline": "November 2019 to Present"
      },
      {
      "company": "Americas Business Express - Johnson City, NY",
      "position": "Driver/Warehouse",
      "timeline": "September 2018 to January 2019"
      },
      {
      "company": "Brenda Uni",
      "position": "Teachers Aide and Family Life Specialist",
      "timeline": "December 2017 to June 2018"
      },
      
        # in our data base the documnet match all three feild it shoulb be return


 # respose :->
      
                            "status": true,
                                "message": "ressume you want",
                                "data": [
                                    {
                                        "_id": "62bd98c75693096630d730ce",
                                        "title": "Mrs",
                                        "name": "Vaibhav Patel",
                                        "phone": "9922295271",
                                        "email": "vaibhav@gmail.com",
                                        "address": "Gujrat",
                                        "education": "B PharmL",
                                        "skills": [
                                            "HTML",
                                            "CSS",
                                            "JAVASCRIPT",
                                            "MONGODB",
                                            "NODEJS"
                                        ],
                                        "experience": [
                                            "No Exprience till Now"
                                        ],
                                        "createdAt": "2022-06-30T12:36:23.375Z",
                                        "updatedAt": "2022-06-30T12:36:23.375Z",
                                        "__v": 0
                                    }
                                ]
                            }
 
      {
      "company": "A.L. George - Binghamton, NY",
      "position": "Driver Helper route delivery",
      "timeline": "April 2017 to November 2017"
      }
    ],
    "total_experience": 2154,
    "total_percentile_score": 100.0
  }
}
Copy
