## Generated Story -3440411185806829378
* greet
    - utter_greet
* name{"name": "nada"}
    - slot{"name": "nada"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "web developer"}
    - form: job_form
    - slot{"job_title": "web developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "master''s degree"}
    - form: job_form
    - slot{"degree_name": "master''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "skilled"}
    - form: job_form
    - slot{"career_level": "skilled"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "full-time"}
    - form: job_form
    - slot{"employment_type": "full-time"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": ["DevOps", "PHP", "javascript", "sql", "nosql"]"}
    - form: job_form
    - slot{"competency": ["DevOps", "PHP", "javascript", "sql", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "tunis"}
    - form: job_form
    - slot{"location": "tunis"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "target"}
    - form: job_form
    - slot{"company": "target"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 781, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554507, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 616, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552379621, \"applied_before\": 1560628800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 1, \"salary\": \"OMR\", \"location\": \"dach\", \"job_description\": \"<p>BEST JOB EVER yes</p>\\n\", \"compentency\": [\"JavaScript Framework\", \"NoSQL\", \"DevOps\", \"Java (computer programming)\", \"SQL\", \"utilise machine learning\", \"JavaScript\", \"PHP\", \"ASP.NET\"]}", "{\"job_id\": 788, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555565, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}", "{\"job_id\": 791, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555462, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}", "{\"job_id\": 587, \"job_title\": \"web dach developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1544011056, \"applied_before\": 1553896800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 3, \"salary\": null, \"location\": \"tunisia\", \"job_description\": \"<p>test</p>\\n\", \"compentency\": [\"write Javanese\", \"DevOps\", \"SQL\", \"utilise machine learning\"]}", "{\"job_id\": 784, \"job_title\": \"software developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554480, \"applied_before\": 1561665600, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><span style=\\\"color: rgba(0,0,0,0.87);background-color: rgb(255,255,255);font-size: 16px;font-family: Roboto, sans-serif;\\\">Experience in planning and delivering software platforms used across multiple products and organizational units.</span>&nbsp;</p>\\n\", \"compentency\": [\"PHP\", \"NoSQL\", \"Java (computer programming)\"]}", "{\"job_id\": 789, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555554, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"Target\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\"]}", "{\"job_id\": 780, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554529, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"Target\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\"]}", "{\"job_id\": 797, \"job_title\": \"backend developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555503, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"Target\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story 2316611506791797464
* greet
    - utter_greet
* name{"name": "omar"}
    - slot{"name": "omar"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "fullstack"}
    - slot{"job_title": "fullstack"}
    - form: job_form
    - slot{"job_title": "fullstack"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "master''s degree"}
    - form: job_form
    - slot{"degree_name": "master''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "supervisor"}
    - form: job_form
    - slot{"career_level": "supervisor"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "Casual"}
    - form: job_form
    - slot{"employment_type": "Casual"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": "nosql"}
    - slot{"competency": ["DevOps", "nosql"]}
    - form: job_form
    - slot{"competency": ["DevOps", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "tunisia"}
    - slot{"location": "tunisia"}
    - form: job_form
    - slot{"location": "tunisia"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "target"}
    - slot{"company": "target"}
    - form: job_form
    - slot{"company": "target"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 791, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555462, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story 2316611506791797464
* greet
    - utter_greet
* name{"name": "nada"}
    - slot{"name": "nada"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "frontend developer"}
    - form: job_form
    - slot{"job_title": "frontend developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "bachelor''s degree"}
    - form: job_form
    - slot{"degree_name": "bachelor''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "supervisor"}
    - form: job_form
    - slot{"career_level": "supervisor"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "Casual"}
    - form: job_form
    - slot{"employment_type": "Casual"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": "nosql"}
    - slot{"competency": ["DevOps", "nosql"]}
    - form: job_form
    - slot{"competency": ["DevOps", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "tunisia"}
    - slot{"location": "tunisia"}
    - form: job_form
    - slot{"location": "tunisia"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "target"}
    - slot{"company": "target"}
    - form: job_form
    - slot{"company": "target"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 791, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555462, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

<!--- *************************************just************************************* --->

## Generated Story -34404111858068293789
* greet
    - utter_greet
* name{"name": "ahmed"}
    - slot{"name": "ahmed"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "frontend developer"}
    - slot{"job_title": "frontend developer"}
    - form: job_form
    - slot{"job_title": "frontend developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "master''s degree"}
    - form: job_form
    - slot{"degree_name": "master''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "un-skilled"}
    - form: job_form
    - slot{"career_level": "un-skilled"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "part-time"}
    - form: job_form
    - slot{"employment_type": "part-time"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": "nosql"}
    - slot{"competency": ["DevOps", "PHP", "javascript", "sql", "nosql"]}
    - form: job_form
    - slot{"competency": ["DevOps", "PHP", "javascript", "sql", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "tunisia"}
    - slot{"location": "tunisia"}
    - form: job_form
    - slot{"location": "tunisia"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "target"}
    - slot{"company": "target"}
    - form: job_form
    - slot{"company": "target"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 781, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554507, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 616, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552379621, \"applied_before\": 1560628800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 1, \"salary\": \"OMR\", \"location\": \"dach\", \"job_description\": \"<p>BEST JOB EVER yes</p>\\n\", \"compentency\": [\"JavaScript Framework\", \"NoSQL\", \"DevOps\", \"Java (computer programming)\", \"SQL\", \"utilise machine learning\", \"JavaScript\", \"PHP\", \"ASP.NET\"]}", "{\"job_id\": 788, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555565, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}", "{\"job_id\": 791, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555462, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}", "{\"job_id\": 587, \"job_title\": \"web dach developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1544011056, \"applied_before\": 1553896800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 3, \"salary\": null, \"location\": \"tunisia\", \"job_description\": \"<p>test</p>\\n\", \"compentency\": [\"write Javanese\", \"DevOps\", \"SQL\", \"utilise machine learning\"]}", "{\"job_id\": 784, \"job_title\": \"software developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554480, \"applied_before\": 1561665600, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><span style=\\\"color: rgba(0,0,0,0.87);background-color: rgb(255,255,255);font-size: 16px;font-family: Roboto, sans-serif;\\\">Experience in planning and delivering software platforms used across multiple products and organizational units.</span>&nbsp;</p>\\n\", \"compentency\": [\"PHP\", \"NoSQL\", \"Java (computer programming)\"]}", "{\"job_id\": 789, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555554, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"Target\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\"]}", "{\"job_id\": 780, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554529, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"Target\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\"]}", "{\"job_id\": 797, \"job_title\": \"backend developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555503, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"Target\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story 2316615067917974643
* greet
    - utter_greet
* name{"name": "mahdir"}
    - slot{"name": "mahdi"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "fullstack developer"}
    - slot{"job_title": "fullstack developer"}
    - form: job_form
    - slot{"job_title": "fullstack developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "master''s degree"}
    - form: job_form
    - slot{"degree_name": "master''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "supervisor"}
    - form: job_form
    - slot{"career_level": "supervisor"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "Casual"}
    - form: job_form
    - slot{"employment_type": "Casual"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": "nosql"}
    - slot{"competency": ["DevOps", "nosql"]}
    - form: job_form
    - slot{"competency": ["DevOps", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "lac"}
    - slot{"location": "lac"}
    - form: job_form
    - slot{"location": "lac"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "target"}
    - slot{"company": "target"}
    - form: job_form
    - slot{"company": "target"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 791, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555462, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story 23166115067917974644
* greet
    - utter_greet
* name{"name": "radhi"}
    - slot{"name": "radhi"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "frontend developer"}
    - form: job_form
    - slot{"job_title": "frontend developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "bachelor''s degree"}
    - form: job_form
    - slot{"degree_name": "bachelor''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "supervisor"}
    - form: job_form
    - slot{"career_level": "supervisor"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "Casual"}
    - form: job_form
    - slot{"employment_type": "Casual"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": "nosql"}
    - slot{"competency": ["DevOps", "nosql","JEE"]}
    - form: job_form
    - slot{"competency": ["DevOps", "nosql","JEE"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "tunisia"}
    - slot{"location": "tunisia"}
    - form: job_form
    - slot{"location": "tunisia"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "target"}
    - slot{"company": "target"}
    - form: job_form
    - slot{"company": "target"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 791, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555462, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet


## Generated Story -1593273812615360576
* greet
    - utter_greet
* name{"name": "radhi"}
    - slot{"name": "radhi"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* inform{"degree_name": "master''s degree", "job_title": "web developer"}
    - slot{"job_title": "web developer"}
    - slot{"degree_name": "master''s degree"}
    - utter_ask_industry
* inform{"industry": "Information and Cultural Industriesy"}
    - job_form
    - form{"name": "job_form"}
    - slot{"industry": null}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "skilled"}
    - form: job_form
    - slot{"career_level": "skilled"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "full-time"}
    - form: job_form
    - slot{"employment_type": "full-time"}
    - slot{"requested_slot": "competency"}
* form: inform{"employment_type": "full-time"}
    - form: job_form
    - slot{"employment_type": "full-time"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": "nosql"}
    - slot{"competency": ["JEE", "nosql"]}
    - form: job_form
    - slot{"competency": ["JEE", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "tunis"}
    - slot{"location": "tunis"}
    - form: job_form
    - slot{"location": "tunis"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "target"}
    - slot{"company": "target"}
    - form: job_form
    - slot{"company": "target"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 616, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552379621, \"applied_before\": 1560628800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 1, \"salary\": \"OMR\", \"location\": \"dach\", \"job_description\": \"<p>BEST JOB EVER yes</p>\\n\", \"compentency\": [\"JavaScript Framework\", \"NoSQL\", \"DevOps\", \"Java (computer programming)\", \"SQL\", \"utilise machine learning\", \"JavaScript\", \"PHP\", \"ASP.NET\"]}", "{\"job_id\": 781, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554507, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 784, \"job_title\": \"software developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554480, \"applied_before\": 1561665600, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><span style=\\\"color: rgba(0,0,0,0.87);background-color: rgb(255,255,255);font-size: 16px;font-family: Roboto, sans-serif;\\\">Experience in planning and delivering software platforms used across multiple products and organizational units.</span>&nbsp;</p>\\n\", \"compentency\": [\"PHP\", \"NoSQL\", \"Java (computer programming)\"]}", "{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story -2778626575161102405
* greet
    - utter_greet
* name{"name": "mahdi"}
    - slot{"name": "mahdi"}
    - utter_ask_howcanhelp
* newjoob
    - utter_ask_newjob
* inform{"location": "tunis"}
    - slot{"location": "tunis"}
    - job_form
    - form{"name": "job_form"}
    - slot{"location": "tunis"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "software developer"}
    - slot{"job_title": "software developer"}
    - form: job_form
    - slot{"job_title": "software developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "Bachelor's Degreee"}
    - form: job_form
    - slot{"degree_name": null}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "bachelor''s degree"}
    - form: job_form
    - slot{"degree_name": "bachelor''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "skilled"}
    - form: job_form
    - slot{"career_level": "skilled"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "daily hire and weekly hire"}
    - form: job_form
    - slot{"employment_type": "daily hire and weekly hire"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": "sql"}
    - slot{"competency": ["JEE", "sql"]}
    - form: job_form
    - slot{"competency": ["JEE", "sql"]}
    - slot{"requested_slot": "company"}
* form: inform{"company": "facebook"}
    - slot{"company": "facebook"}
    - form: job_form
    - slot{"company": "facebook"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 790, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555574, \"applied_before\": 1565294400, \"degree_level\": \"Bachelor's Degree\", \"career_level\": \"Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><span style=\\\"color: rgba(0,0,0,0.87);background-color: rgb(255,255,255);font-size: 16px;font-family: Roboto, sans-serif;\\\">The role is responsible for designing, coding and modifying websites, from layout to function and according to a client's specifications. Strive to create visually appealing sites that feature user-friendly design and clear navigation.</span>&nbsp;</p>\\n\", \"compentency\": [\"PHP\", \"ASP.NET\", \"JavaScript\", \"NoSQL\", \"SQL\", \"DevOps\", \"utilise machine learning\", \"utilise advanced clinical skills\", \"utilise machine learning\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story 3041817968370860412
* greet
    - utter_greet
* name{"name": "mahdi"}
    - slot{"name": "mahdi"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* inform{"job_title": "software developer", "location": "tunis"}
    - form: job_form
    - slot{"job_title": "software developer"}
    - slot{"location": "tunis"}    
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "master''s degree"}
    - form: job_form
    - slot{"degree_name": "master''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "Un-Skilled", "competency": "nosql"}
    - job_form
    - slot{"competency": "nosql"}
    - slot{"career_level": "Un-Skilled"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "full-time", "company": "target"}
    - slot{"company": "target"}
    - form: job_form
    - slot{"company": "target"}
    - slot{"employment_type": "full-time"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["No job match found"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story -1099335218604143365
* greet
    - utter_greet
* name{"name": "nada"}
    - slot{"name": "nada"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "back end developer"}
    - slot{"job_title": "back end developer"}
    - form: job_form
    - slot{"job_title": "back end developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "master''s degree"}
    - form: job_form
    - slot{"degree_name": "master''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "professional"}
    - job_form
    - slot{"career_level": "professional"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "Probation"}
    - form: job_form
    - slot{"employment_type": "Probation"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": "nosql"}
    - slot{"competency": [" JavaScript Framework", "nosql"]}
    - form: job_form
    - slot{"competency": [" JavaScript Framework", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "tunis", "company": "target"}
    - slot{"company": "target"}
    - slot{"location": "tunis"}
    - form: job_form
    - slot{"company": "target"}
    - slot{"location": "tunis"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 616, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552379621, \"applied_before\": 1560628800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 1, \"salary\": \"OMR\", \"location\": \"dach\", \"job_description\": \"<p>BEST JOB EVER yes</p>\\n\", \"compentency\": [\"JavaScript Framework\", \"NoSQL\", \"DevOps\", \"Java (computer programming)\", \"SQL\", \"utilise machine learning\", \"JavaScript\", \"PHP\", \"ASP.NET\"]}", "{\"job_id\": 781, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554507, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 784, \"job_title\": \"software developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554480, \"applied_before\": 1561665600, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><span style=\\\"color: rgba(0,0,0,0.87);background-color: rgb(255,255,255);font-size: 16px;font-family: Roboto, sans-serif;\\\">Experience in planning and delivering software platforms used across multiple products and organizational units.</span>&nbsp;</p>\\n\", \"compentency\": [\"PHP\", \"NoSQL\", \"Java (computer programming)\"]}", "{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story 6157510179309223624
* greet
    - utter_greet
* name{"name": "tarek"}
    - slot{"name": "tarek"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "back end developer"}
    - form: job_form
    - slot{"job_title": "back end developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "Higher Diploma"}
    - form: job_form
    - slot{"degree_name": "Higher Diploma"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "Un-Skilled"}
    - form: job_form
    - slot{"career_level": "Un-Skilled"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "Contractual"}
    - form: job_form
    - slot{"employment_type": "Contractual"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": "JEE"}
    - slot{"competency": ["react", "NoSql", "JEE"]}
    - form: job_form
    - slot{"competency": ["react", "NoSql", "JEE"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "tunisia"}
    - slot{"location": "tunisia"}
    - form: job_form
    - slot{"location": "tunisia"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "vermeg"}
    - slot{"company": "vermeg"}
    - form: job_form
    - slot{"company": "vermeg"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["No job match found"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story 1286803451675931544
* greet
    - utter_greet
* name{"name": "wajih"}
    - slot{"name": "wajih"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "back end developer"}
    - form: job_form
    - slot{"job_title": "back end developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "vocational diploma"}
    - form: job_form
    - slot{"degree_name": "vocational diploma"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "Un-Skilled"}
    - form: job_form
    - slot{"career_level": "Un-Skilled"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "Outworkers"}
    - form: job_form
    - slot{"employment_type": "Outworkers"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": " JavaScript Framework"}
    - slot{"competency": [" JavaScript Framework"]}
    - form: job_form
    - slot{"competency": " JavaScript Framework"}
    - slot{"requested_slot": "location"}
* form: inform{"location": "tunisia"}
    - slot{"location": "tunisia"}
    - form: job_form
    - slot{"location": "tunisia"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "vermeg"}
    - slot{"company": "vermeg"}
    - form: job_form
    - slot{"company": "vermeg"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["No job match found"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story 12868034516759315442
* greet
    - utter_greet
* name{"name": "mahdi"}
    - slot{"name": "mahdi"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "web developer"}
    - form: job_form
    - slot{"job_title": "web developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "vocational diploma"}
    - form: job_form
    - slot{"degree_name": "vocational diploma"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "Skilled"}
    - form: job_form
    - slot{"career_level": "Skilled"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "shiftworkers"}
    - form: job_form
    - slot{"employment_type": "shiftworkers"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": " JavaScript Framework"}
    - slot{"competency": [" JavaScript Framework","JEE"]}
    - form: job_form
    - slot{"competency": [" JavaScript Framework","JEE"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "tunisia"}
    - slot{"location": "tunisia"}
    - form: job_form
    - slot{"location": "tunisia"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "facebook"}
    - slot{"company": "facebook"}
    - form: job_form
    - slot{"company": "facebook"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["No job match found"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story -34404111858068293788
* greet
    - utter_greet
* name{"name": "nada"}
    - slot{"name": "nada"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "frontend developer"}
    - form: job_form
    - slot{"job_title": "frontend developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "master''s degree"}
    - form: job_form
    - slot{"degree_name": "master''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "skilled"}
    - form: job_form
    - slot{"career_level": "skilled"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "part-time"}
    - form: job_form
    - slot{"employment_type": "part-time"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": [ "sql", "nosql"]}
    - form: job_form
    - slot{"competency": ["sql", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "tunis"}
    - form: job_form
    - slot{"location": "tunis"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "target"}
    - form: job_form
    - slot{"company": "target"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 781, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554507, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 616, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552379621, \"applied_before\": 1560628800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 1, \"salary\": \"OMR\", \"location\": \"dach\", \"job_description\": \"<p>BEST JOB EVER yes</p>\\n\", \"compentency\": [\"JavaScript Framework\", \"NoSQL\", \"DevOps\", \"Java (computer programming)\", \"SQL\", \"utilise machine learning\", \"JavaScript\", \"PHP\", \"ASP.NET\"]}", "{\"job_id\": 788, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555565, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}", "{\"job_id\": 791, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555462, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}", "{\"job_id\": 587, \"job_title\": \"web dach developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1544011056, \"applied_before\": 1553896800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 3, \"salary\": null, \"location\": \"tunisia\", \"job_description\": \"<p>test</p>\\n\", \"compentency\": [\"write Javanese\", \"DevOps\", \"SQL\", \"utilise machine learning\"]}", "{\"job_id\": 784, \"job_title\": \"software developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554480, \"applied_before\": 1561665600, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><span style=\\\"color: rgba(0,0,0,0.87);background-color: rgb(255,255,255);font-size: 16px;font-family: Roboto, sans-serif;\\\">Experience in planning and delivering software platforms used across multiple products and organizational units.</span>&nbsp;</p>\\n\", \"compentency\": [\"PHP\", \"NoSQL\", \"Java (computer programming)\"]}", "{\"job_id\": 789, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555554, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"Target\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\"]}", "{\"job_id\": 780, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554529, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"Target\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\"]}", "{\"job_id\": 797, \"job_title\": \"backend developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555503, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"Target\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story -344041118580682937880
* greet
    - utter_greet
* name{"name": "nada"}
    - slot{"name": "nada"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "frontend developer"}
    - form: job_form
    - slot{"job_title": "frontend developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "bachelor''s degree"}
    - form: job_form
    - slot{"degree_name": "bachelor''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "un-skilled"}
    - form: job_form
    - slot{"career_level": "un-skilled"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "part-time"}
    - form: job_form
    - slot{"employment_type": "part-time"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": [ "sql", "nosql"]}
    - form: job_form
    - slot{"competency": ["sql", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "paris"}
    - form: job_form
    - slot{"location": "paris"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "target"}
    - form: job_form
    - slot{"company": "target"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 781, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554507, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 616, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552379621, \"applied_before\": 1560628800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 1, \"salary\": \"OMR\", \"location\": \"dach\", \"job_description\": \"<p>BEST JOB EVER yes</p>\\n\", \"compentency\": [\"JavaScript Framework\", \"NoSQL\", \"DevOps\", \"Java (computer programming)\", \"SQL\", \"utilise machine learning\", \"JavaScript\", \"PHP\", \"ASP.NET\"]}", "{\"job_id\": 788, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555565, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story -3440411185806829880
* greet
    - utter_greet
* name{"name": "nada"}
    - slot{"name": "nada"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "developer"}
    - form: job_form
    - slot{"job_title": "developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "bachelor''s degree"}
    - form: job_form
    - slot{"degree_name": "bachelor''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "senior management"}
    - form: job_form
    - slot{"career_level": "senior management"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "casual"}
    - form: job_form
    - slot{"employment_type": "casual"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": [ "sql", "nosql","PHP"]}
    - form: job_form
    - slot{"competency": ["sql", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "paris"}
    - form: job_form
    - slot{"location": "paris"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "target"}
    - form: job_form
    - slot{"company": "target"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 781, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554507, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 616, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552379621, \"applied_before\": 1560628800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 1, \"salary\": \"OMR\", \"location\": \"dach\", \"job_description\": \"<p>BEST JOB EVER yes</p>\\n\", \"compentency\": [\"JavaScript Framework\", \"NoSQL\", \"DevOps\", \"Java (computer programming)\", \"SQL\", \"utilise machine learning\", \"JavaScript\", \"PHP\", \"ASP.NET\"]}", "{\"job_id\": 788, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555565, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story -34404111858068293711880
* greet
    - utter_greet
* name{"name": "nada"}
    - slot{"name": "nada"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "developer"}
    - form: job_form
    - slot{"job_title": "developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "bachelor''s degree"}
    - form: job_form
    - slot{"degree_name": "bachelor''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "supervisor"}
    - form: job_form
    - slot{"career_level": "supervisor"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "casual"}
    - form: job_form
    - slot{"employment_type": "casual"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": [ "sql", "nosql","PHP"]}
    - form: job_form
    - slot{"competency": ["sql", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "paris"}
    - form: job_form
    - slot{"location": "paris"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "target"}
    - form: job_form
    - slot{"company": "target"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 781, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554507, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 616, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552379621, \"applied_before\": 1560628800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 1, \"salary\": \"OMR\", \"location\": \"dach\", \"job_description\": \"<p>BEST JOB EVER yes</p>\\n\", \"compentency\": [\"JavaScript Framework\", \"NoSQL\", \"DevOps\", \"Java (computer programming)\", \"SQL\", \"utilise machine learning\", \"JavaScript\", \"PHP\", \"ASP.NET\"]}", "{\"job_id\": 788, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555565, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story -342404111858068293711880
* greet
    - utter_greet
* name{"name": "hamdi"}
    - slot{"name": "hamdi"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "developer"}
    - form: job_form
    - slot{"job_title": "developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "bachelor''s degree"}
    - form: job_form
    - slot{"degree_name": "bachelor''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "supervisor"}
    - form: job_form
    - slot{"career_level": "supervisor"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "casual"}
    - form: job_form
    - slot{"employment_type": "casual"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": [ "sql", "nosql","PHP"]}
    - form: job_form
    - slot{"competency": ["sql", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "paris"}
    - form: job_form
    - slot{"location": "paris"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "google"}
    - form: job_form
    - slot{"company": "google"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 781, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554507, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 616, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552379621, \"applied_before\": 1560628800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 1, \"salary\": \"OMR\", \"location\": \"dach\", \"job_description\": \"<p>BEST JOB EVER yes</p>\\n\", \"compentency\": [\"JavaScript Framework\", \"NoSQL\", \"DevOps\", \"Java (computer programming)\", \"SQL\", \"utilise machine learning\", \"JavaScript\", \"PHP\", \"ASP.NET\"]}", "{\"job_id\": 788, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555565, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story -3424041118580682934571331880
* greet
    - utter_greet
* name{"name": "nour"}
    - slot{"name": "nour"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "developer"}
    - form: job_form
    - slot{"job_title": "developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "(advanced diploma) technical colleges"}
    - form: job_form
    - slot{"degree_name": "(advanced diploma) technical colleges"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "supervisor"}
    - form: job_form
    - slot{"career_level": "supervisor"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "casual"}
    - form: job_form
    - slot{"employment_type": "casual"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": [ "sql", "nosql","PHP"]}
    - form: job_form
    - slot{"competency": ["sql", "nosql"]}
    - slot{"requested_slot": "location"}
* form: inform{"location": "paris"}
    - form: job_form
    - slot{"location": "paris"}
    - slot{"requested_slot": "company"}
* form: inform{"company": "google"}
    - form: job_form
    - slot{"company": "google"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 792, \"job_title\": \"fullstack developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555540, \"applied_before\": 1560283200, \"degree_level\": \"(advanced diploma) technical colleges\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"lac\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\", \"SQL\", \"PHP\", \"utilise machine learning\", \"communication\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 781, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554507, \"applied_before\": 1559332800, \"degree_level\": \"(advanced diploma) technical colleges\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 616, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552379621, \"applied_before\": 1560628800, \"degree_level\": \"(advanced diploma) technical colleges\", \"career_level\": \"Semi-Skilled\", \"experience\": 1, \"salary\": \"OMR\", \"location\": \"dach\", \"job_description\": \"<p>BEST JOB EVER yes</p>\\n\", \"compentency\": [\"JavaScript Framework\", \"NoSQL\", \"DevOps\", \"Java (computer programming)\", \"SQL\", \"utilise machine learning\", \"JavaScript\", \"PHP\", \"ASP.NET\"]}", "{\"job_id\": 788, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555565, \"applied_before\": 1559332800, \"degree_level\": \"(advanced diploma) technical colleges\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet
## Generated Story -1304326258152322668
* greet
    - utter_greet
* name{"name": "yoser"}
    - slot{"name": "yoser"}
    - utter_ask_howcanhelp
* inform{"job_title": "web developer", "location": "tunis", "company": "target"}
    - slot{"company": "target"}
    - slot{"job_title": "web developer"}
    - slot{"location": "tunis"}
    - job_form
    - form{"name": "job_form"}
    - slot{"job_title": "web developer"}
    - slot{"location": "tunis"}
    - slot{"company": "target"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "PH.D."}
    - form: job_form
    - slot{"degree_name": "PH.D."}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "professional"}
    - form: job_form
    - slot{"career_level": "professional"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "part-time"}
    - form: job_form
    - slot{"employment_type": "part-time"}
    - slot{"requested_slot": "competency"}
* name{"competency": " JavaScript Framework"}
    - job_form
    - slot{"competency": [" JavaScript Framework"]}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["No job match found"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet


## Generated Story -6216323498629393162
* greet
    - utter_greet
* name{"name": "omar"}
    - slot{"name": "omar"}
    - utter_ask_howcanhelp
* newjoob
    - utter_ask_newjob
* inform
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "web developper"}
    - slot{"job_title": "web developper"}
    - form: job_form
    - slot{"job_title": "web developper"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "information and cultural industries"}
    - form: job_form
    - slot{"industry": "information and cultural industries"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "master''s degree"}
    - form: job_form
    - slot{"degree_name": "master''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "semi-skilled"}
    - form: job_form
    - slot{"career_level": "semi-skilled"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "full-time", "company": "target", "location": "tunis"}
    - slot{"company": "target"}
    - slot{"location": "tunis"}
    - form: job_form
    - slot{"location": "tunis"}
    - slot{"company": "target"}
    - slot{"employment_type": "full-time"}
    - slot{"requested_slot": "competency"}
* form: inform{"competency": "nosql"}
    - slot{"competency": ["Java (computer programming)", "nosql"]}
    - form: job_form
    - slot{"competency": ["Java (computer programming)", "nosql"]}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 616, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552379621, \"applied_before\": 1560628800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 1, \"salary\": \"OMR\", \"location\": \"dach\", \"job_description\": \"<p>BEST JOB EVER yes</p>\\n\", \"compentency\": [\"JavaScript Framework\", \"NoSQL\", \"DevOps\", \"Java (computer programming)\", \"SQL\", \"utilise machine learning\", \"JavaScript\", \"PHP\", \"ASP.NET\"]}", "{\"job_id\": 781, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554507, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\", \"NoSQL\", \"JavaScript\"]}", "{\"job_id\": 780, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552554529, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"Target\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\"]}", "{\"job_id\": 788, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555565, \"applied_before\": 1559332800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"tunis\", \"job_description\": \"<p><em>This web developer sample job description can assist in your creating a job application that will attract job candidates who are qualified for the job. Feel free to revise this job description to meet your specific job duties and job requirements.</em>&nbsp;</p>\\n\", \"compentency\": [\"SQL\", \"Java (computer programming)\", \"DevOps\", \"PHP\", \"Python (computer programming)\"]}", "{\"job_id\": 789, \"job_title\": \"web programming\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552555554, \"applied_before\": 1560283200, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 0, \"salary\": null, \"location\": \"Target\", \"job_description\": \"<p>&nbsp;We are looking for a qualified Application Developer to<br>design and code functional programs and applications. You will work as part of<br>a team and individually with little supervision.&nbsp;</p>\\n<p>A great Application Developer has excellent knowledge of at<br>least one programming language. They must be familiar with a variety of<br>operating systems and platforms. The ideal candidate will also have an<br>analytical mindset and a keen eye for detail.&nbsp;</p>\\n<p>The goal is to write \\u201cclean\\u201d and flawless code to produce<br>fully functional software applications according to requirements.&nbsp;&nbsp;&nbsp;</p>\\n\", \"compentency\": [\"Java (computer programming)\", \"principles of artificial intelligence\", \"DevOps\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet

## Generated Story -8611798167337776973
* greet
    - utter_greet
* name{"name": "zahra"}
    - slot{"name": "zahra"}
    - utter_ask_howcanhelp
* request_job
    - job_form
    - form{"name": "job_form"}
    - slot{"requested_slot": "job_title"}
* form: inform{"job_title": "frontend developer", "location": "london"}
    - slot{"job_title": "frontend developer"}
    - slot{"location": "london"}
    - form: job_form
    - slot{"location": "london"}
    - slot{"job_title": "frontend developer"}
    - slot{"requested_slot": "industry"}
* form: inform{"industry": "Utilities"}
    - form: job_form
    - slot{"industry": "Utilities"}
    - slot{"requested_slot": "degree_name"}
* form: inform{"degree_name": "master''s degree", "company": "appel"}
    - slot{"company": "appel"}
    - form: job_form
    - slot{"company": "appel"}
    - slot{"degree_name": "master''s degree"}
    - slot{"requested_slot": "career_level"}
* form: inform{"career_level": "professional", "competency": "JavaScript Framework"}
    - slot{"competency": ["JavaScript Framework"]}
    - form: job_form
    - slot{"competency": "JavaScript Framework"}
    - slot{"career_level": "professional"}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "Fixed term"}
    - form: job_form
    - slot{"employment_type": null}
    - slot{"requested_slot": "employment_type"}
* form: inform{"employment_type": "Probation"}
    - form: job_form
    - slot{"employment_type": "Probation"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_ask_moreupdates
* affirm
    - utter_ack_makeresearch
* affirm
    - utter_ack_dosearch
    - action_search_jobs
    - slot{"matches": ["{\"job_id\": 616, \"job_title\": \"web developer\", \"company\": \"Target Oilfield Services L.L.C.\", \"posting_date\": 1552379621, \"applied_before\": 1560628800, \"degree_level\": \"Master's Degree\", \"career_level\": \"Semi-Skilled\", \"experience\": 1, \"salary\": \"OMR\", \"location\": \"dach\", \"job_description\": \"<p>BEST JOB EVER yes</p>\\n\", \"compentency\": [\"JavaScript Framework\", \"NoSQL\", \"DevOps\", \"Java (computer programming)\", \"SQL\", \"utilise machine learning\", \"JavaScript\", \"PHP\", \"ASP.NET\"]}"]}
    - action_get_jobs
* thankyou
    - utter_goodbye
* greet
