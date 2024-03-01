# Rust-Fullstack-Tide-Postgres-Crud-API


### Stack

- Tide
- sqlx
- postgres
- Tera

### Instructions

- Make sure Postgres is installed and you have a database called "tide". since that's the database we connect with
- Make sure there's a table called "dinos" in the postgresdb, you can run this command - 
`CREATE TABLE dinos (
    id uuid NOT NULL,
    name text NOT NULL,
    weight integer NOT NULL,
    diet text NOT NULL,
    user_id text
);`
- Especially if you're not comfortable running the schema.sql file
- Change the sample.env file to just `.env`
- You will get your `OAUTH_GOOGLE_CLIENT_ID` and `OAUTH_GOOGLE_CLIENT_SECRET` from google, just search for google oauth and create a project

---

