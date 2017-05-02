# pethotel

```CREATE TABLE pets (
   id SERIAL PRIMARY KEY NOT NULL,
   name VARCHAR(20),
   color VARCHAR(20),
   breed VARCHAR (20)
   
);

CREATE TABLE pets (
   id SERIAL PRIMARY KEY NOT NULL,
   name VARCHAR(20),
 
   );
CREATE TABLE stays (
   id SERIAL PRIMARY KEY NOT NULL,
   pet_id INTEGER references pets (id),
   check_in TIMESTAMPS WITH TIME ZONE,
   check_out TIMESTAMPS WITH TIME ZONE

   
);
    

CREATE TABLE owner_pets (
   owner_id INTEGER references owner(id),
   pets_id INTEGER references pets(id),
   
);```

