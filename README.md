# Health_Cloud

select Id, PersonContactId, LastName,(select id from Candidate_Profiles__r),(select id from HealthcareProviders) from Account where IsPersonAccount =true AND PersonEmail = 'priya.ramanathan@example.test'
