# miniSearchArticle
# Mini Search Engine for Articles

This is a simple **Mini Search Engine** that allows users to add, search, and retrieve articles. The articles can be searched by title, content, or tags. The system also supports sorting search results by relevance and date. This project is designed as a backend application using **Node.js**.

## Features

- **Add Articles**: Add articles with a title, content, and tags.
- **Search Articles**: Search articles by keywords in the title or content.
- **Sort Search Results**: Sort search results by relevance or date.
- **Retrieve Article by ID**: Get the full details of an article using its ID.

## Endpoints

### 1. Add Article (POST `/articles`)

This endpoint allows you to add a new article to the system.

**Request Body**:
```json
{
  "title": "Understanding JavaScript Closures",
  "content": "Closures are functions that have access to variables from another function’s scope.",
  "tags": ["JavaScript", "Closures", "Programming"]
}
### 2.Search by relevance
GET /articles/search?keyword=JavaScript
### 2.Search by id
GET /articles/id
