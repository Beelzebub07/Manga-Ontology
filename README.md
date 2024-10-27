Manga Ontology
Supervisor: Prof. Louise Leenen
Student: Keeveshin Perumal
Student Number: 4124559
Email: 4124559@myuwc.ac.za

Project Overview
The Manga Ontology project is a structured representation of information within the domain of manga. It organizes key entities, attributes, and relationships, enabling advanced reasoning, insightful queries, and a more detailed understanding of manga data than traditional database structures. The ontology is designed to support applications such as search and recommendation systems by providing formalized relationships between manga elements, such as authors, characters, genres, and publishers.

Contents
Classes: Core components of manga information.
Object Properties: Relationships between the classes.
Data Properties: Specific attributes for each entity.
Individuals: Real-world examples from popular manga.

Requirements
Protégé: The ontology was developed and tested in Protégé, a tool for building ontologies in the Web Ontology Language (OWL).

Classes
The main classes represent the foundational entities in the manga domain:
Author: Represents creators (writers, illustrators) responsible for manga titles.
Manga: Represents individual manga titles, such as Naruto or One Piece.
Character: Represents fictional characters within the manga.
Genre: Represents the category of manga, e.g., Shonen, Shojo, Seinen.
Publisher: Represents publishing companies, such as Shueisha and Kodansha.
Volume: Represents collections of chapters within a manga series.
Chapter: Represents individual segments within a manga.

Object Properties
The ontology includes several object properties to define relationships between classes:
belongToGenre: Links manga to their respective genre(s).
containsChapter: Connects a manga to its chapters.
hasAuthor: Links a manga title to its author.
hasChapter: Connects volumes to their chapters.
hasCharacter: Associates manga titles with their characters.
hasPublishedDate: Links manga, chapters, or volumes to their publication dates.
hasPublisher: Connects manga or volumes to their publishers.
hasVolume: Links manga to their volumes.
includesManga: Connects a genre to the manga titles it includes.
isAuthorOf: Reverse of hasAuthor, linking authors to their works.
isChapterOf: Reverse of containsChapter, linking chapters to their manga.
isCharacterIn: Links characters to the manga they appear in.
publishes: Reverse of hasPublisher, linking publishers to their releases.

Data Properties
The ontology uses data properties to represent specific attributes:
authorName: Stores the name of the author.
chapterNumber: Stores the chapter number.
characterName: Stores the name of the character.
genreName: Stores the genre's name.
publisherName: Stores the name of the publisher.
releaseDate: Stores the publication date of manga or chapters.
title: Stores the title of the manga series.
volumeNumber: Stores the volume number.

Individuals
The ontology includes real-world examples to populate and validate relationships. Examples include:
Manga Titles: AttackOnTitan, Naruto, OnePiece, SailorMoon, DeathNote
Authors: EiichiroOda, HajimeIsayama, TsugumiOhba, NaokoTakeuchi
Characters: MonkeyDLuffy, ErenYeager, NarutoUzumaki, UsagiTsukino
Genres: Shonen, Shojo, Seinen
Publishers: Shueisha, Kodansha
Dates: July_22-1997 (One Piece’s release date), September_21-1999 (Naruto’s release date)

Reasoning and Querying
The ontology allows reasoning to infer relationships and conduct complex queries. Examples include:
Finding all manga written by a particular author.
Listing characters within a specific genre, such as Shonen.
Retrieving publication details of manga or their respective volumes and chapters.

Applications and Future Work The Manga Ontology is designed to support enhanced search functionality and potential applications in recommendation systems. Future work may include expanding the ontology to integrate additional entities and refining relationships for more nuanced search capabilities.
