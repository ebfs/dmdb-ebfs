## Task 1: Advantages of DBMSs

* Export for analysis, because data has insights and we have KPIs.
* data integrity, enforcing that a string isn't input as an int. 
* data structure, data should be stored in a sensible hierarchy, ordering, and labeling.

## Task 2: Important concepts

Study this week's lesson slides and other suitable materials and describe each of the following terms briefly in your own words:

1. Data: A unit of value given context.
2. Metadata: Defining properties of data.
3. Data Management: Organising and storing data for fast retrieval and utility.
4. Database Management System (DBMS): A program designed for storing and managing data.
5. Database: A repository of data, hopefully in some structured and connected format.
6. Data redundancy (in the database): Storing useless/duped data.
7. Data independence (in the context of databases): Tiered modification of the databases schemas at a low level (does not affect above).

## Task 3: Primary and foreign keys


1. Who are the members of the band "The Beatles"? 

John Lennon, Paul McCartney, George Harrison, Ringo Starr, George Martin

2. Who is the leader of the band "Queen"?

Freddie Mercury

3. Determine the primary key for each table.

Band PK: band no
Musician PK:  musician no

4. Determine all foreign keys (there are two foreign keys). Also, mention the name of the referenced table.

Band: 'musician no' as 'leader no' from 'Musician'
Musician: 'band no' from 'Band'

5. Consider the tables above. Can a musician belong to more than one band? _Give arguments!_

Should be able to if PK is compound of musician no + band no. Depends on database admin and what whether they want to allow musicians to be in different bands. Context is important (is this for a competition where musician is allowed to be in multiple bands?).

## Task 4

1. Who are the members of the band "AC/DC"?
Angus Young, Brian JOhnson, Malcolm Young

2. Who are the members of the band "Steve Morse Band"?

Steve Morse, Van Romaine, Dave LaRue

3. Determine the primary key for each table.

Band PK: band no
Musician PK:  musician no
Band_Musician PK: band no + musician no

4. Determine all foreign keys (there are three foreign keys). Also, mention the name of the referenced table.

Band: 'musician no' as 'leader no' from 'Musician'
Musician: 'band no' from 'Band'
Band_Musician: 'band no' from Band, 'musician no' from 'Musician'

5. Consider the tables above. Can a musician belong to more than one band? _Give arguments!_

Yes it's allowed since Steve Morse is in multiple bands.