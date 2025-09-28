# 2025 Survey Results
The 2025 Streets PAC NJ survey was provided to all candidates for mayor and
council in Jersey City. We received response from 22 candidates. These answers
are provided in the `responses.json` file. 

## JSON Structure
The JSON comprises an object with two fields: `questions` and `responses`. The 
`questions` field includes the ordered question texts and numbers. Some 
questions include an `extra` field which includes additional HTML text that 
forms part of the question. This was added to allow for text-only questions
as well as text+image questions when displayed at 
[streetspacnj.org](streetspacnj.org).

The `responses` field includes an array of candidates and their responses. 
Each candidate object includes the candidate name, office sought, slate, and 
an array of responses that matches the size of the `questions` field. 

# Copyright
© 2025 Safe Streets Action NJ LLC