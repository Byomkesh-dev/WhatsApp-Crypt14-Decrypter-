# WhatsApp-Crypt14-Decrypter
WhatsApp — the most popular mobile messaging application, stores encrypted
user messages and media files in a database known as msgstore.db.crypt14. It was
doing the encryption of “crypt14” through AES with Galois/Counter Mode
(GCM format). This encrypted database is a requirement in digital forensic
investigation if done by law enforcement agencies. Unfortunately, the specialized
utilities dedicated to decrypting WhatsApp databases are impractical and expensive,
making it an impossible mission for some agencies with tight budgets.
This project offers an affordable solution to decrypt the “msgstore.db.crypt14”,
a Python script that utilizes the AES-GCM algorithm and the WhatsApp key file
to decrypt the crypt14 database file. The script will check if the key file is correct,
find the correct offset, decrypt the database, and then dump it to an SQLite-based
msgstore.db file. A second Python script that accesses a neat form of the database.
This solution is a high-performance yet affordable tool for law enforcement
agencies to parse WhatsApp databases, empowering their investigations within
budgeted costs.
