[← Back to Cybersecurity Track home](../README.md)


# Web Fundamentals Lab

**Stage:** Foundations (Learner) · **When:** Weeks 5–8 · **Time:** 60–90 minutes

**Goal:** Understand how websites, APIs and databases fit together, because you cannot secure what you do not understand.

> [!IMPORTANT]
> Practise only on systems built for it. See the [rules of engagement](../ETHICS-AND-RULES.md).

## What you need
A browser with developer tools; optionally `curl` and SQLite.

## What you will be able to do
- Explain client, server, request and response
- Read status codes and headers in the browser tools
- Describe what an API and a database do
- Explain cookies and sessions at a basic level

## Steps
**Step 1: Watch a request**
Open a public site, press F12, choose the **Network** tab, reload, and click a request. Note the method, status code and headers.

**Step 2: Call a public practice API**
```bash
curl https://httpbin.org/get      # a public test service; check it is available
```
**Step 3: A tiny local database**
```bash
sqlite3 practice.db
```
Then, inside SQLite:
```sql
CREATE TABLE students(id INTEGER PRIMARY KEY, name TEXT);
INSERT INTO students(name) VALUES ('Amina'), ('Brian');
SELECT * FROM students;
```
**Step 4:** Draw how a login form, a server and a database work together.

## ✅ Lab checkpoints
Log these with the Labs/CTF Coordinator. Labs completed, not attendance, count towards your badge.
- [ ] Request and response annotated
- [ ] API call explained
- [ ] Database query run on your own file
- [ ] Diagram of a login flow

## Safety
Use public practice services and your own local files only. Do not send requests to sites you do not own beyond normal browsing.

[← All labs](README.md)
