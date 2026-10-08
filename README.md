# Java Stock Repo

A Java web application for a Java course, built as a Google App Engine project.bchgxhg

## What it does

The welcome page lists available servlets. Exercise 02 (`/iditex`) runs a simple calculation in `IditexServlet` and prints the result as HTML.

## Project layout

- `src/com/myorg/javacourse/` — Java servlets
- `war/` — web content (`index.html`) and App Engine / servlet configuration under `WEB-INF/`
- Eclipse / Google Plugin for Eclipse project files (`.project`, `.classpath`)

## Run locally

This project is set up for Eclipse with the Google Plugin for Eclipse (App Engine SDK 1.9.17). Open it in Eclipse and run it as a Google App Engine web application.

After the local server starts, open:

- `/` — welcome page
- `/iditex` — Exercise 02 math servlet
