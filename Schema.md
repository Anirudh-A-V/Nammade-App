
## Student Information
- Name : String
- email : String (CET id)
- KTU ID/Admission No.  : String/Number  (Optional) (It will serve as an Id)
- Department : String
- Batch : Number (Pass out year)
- ~password : String/Hash~
- Profile Pic : String (URL)
- Registered Events : Array of Events ( referencing Events Collection )

## Club Information (For Devs & Admins)
- Name : String
- Description : String
- Chairperson/Campus Lead : Id referencing that person
- Club Administrator : Id referencing that person (Admin from the Club)
- Contact : Number
- email : String (club email for logging in)
- ~password : String~

## Events
- Name : String
- Date : Date
- Time : Time
- Venue : String
- Club : Club Id referencing that club
- Offline/Online : Boolean
- Join Link : String (URL, For online meets)
- Poster : String (URL)

## Registrations
- Student ID : Referencing the Student Collection
- Date : Date (Date of Registration)
- Time : Time (Time of Registration)
- Notes : String (Relevant Information from Participants)
- _Any Additional Information Specified by the clubs_
