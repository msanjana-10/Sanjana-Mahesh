SELECT *
FROM crime_scene_report
LIMIT 5;
<img width="511" alt="image" src="https://github.com/user-attachments/assets/46759222-abf1-433e-9a16-c4ac0b2dc3cb">

SELECT *
FROM crime_scene_report
WHERE type = "murder";

SELECT *
FROM crime_scene_report
WHERE type = "murder"
AND date = 20180115
AND city = "SQL City";
<img width="625" alt="image" src="https://github.com/user-attachments/assets/8b2b5611-e7db-472a-bd0a-aa3bb0883203">

SELECT *
FROM person
LIMIT 5;
<img width="579" alt="image" src="https://github.com/user-attachments/assets/140e1743-a7a3-45a3-b3b3-4b6c7b044a39">

SELECT *
FROM person

WHERE address_street_name = "Northwestern Dr"
ORDER BY address_number DESC;
<img width="575" alt="image" src="https://github.com/user-attachments/assets/bde3eed2-32cb-4e23-864e-6a5cdb414e4a">

SELECT *
FROM person
WHERE name LIKE '%Annabel%'
AND address_street_name = "Franklin Ave";
![image](https://github.com/user-attachments/assets/5298de44-1e34-4784-945e-132658ac4b8c)

SELECT *
FROM interview
WHERE person_id IN ("14887", "16371");
![image](https://github.com/user-attachments/assets/0e77cb83-c5d2-404e-a3b3-d39bffb122f9)

SELECT *
FROM get_fit_now_check_in
WHERE membership_id LIKE '48Z%'
AND check_in_date = "20180109";
![image](https://github.com/user-attachments/assets/2f2a033a-ab09-44e7-a6c8-4fc67e773a8d)

SELECT *
FROM drivers_license
WHERE gender = "male"
AND plate_number LIKE '%H42W%';
![image](https://github.com/user-attachments/assets/21eff04d-8005-4cc2-b926-b8d6c86483d8)

SELECT *
FROM person
WHERE license_id IN ("423327", "664760");
![image](https://github.com/user-attachments/assets/509b1afa-aa92-4cb8-a896-6bce5f1115c7)

SELECT *
FROM get_fit_now_member

WHERE person_id IN ("51739", "67318");
![image](https://github.com/user-attachments/assets/0bbbf70c-dacc-4c19-a54c-7696a1349bce)






