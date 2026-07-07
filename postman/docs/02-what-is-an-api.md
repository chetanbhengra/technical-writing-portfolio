# What is an API?

| Field | Value |
|--------|-------|
| Audience | Beginners with little or no experience working with APIs |
| Document Type | Concept |
| Estimated Reading Time | 5–7 minutes |
| Prerequisites | What is Postman? |

---

# Purpose

This guide introduces the concept of an Application Programming Interface (API) and explains how APIs enable applications to communicate with one another. After reading this guide, you should understand the basic terminology needed to continue using Postman.

---

# What is an API?

In the previous guide, you learned that Postman is an API platform.

Before using Postman, it is helpful to understand what an API is and why applications use APIs to exchange information.

An **Application Programming Interface (API)** is a set of rules that allows one application to communicate with another.

Instead of accessing another application's database or internal code directly, an application sends a request to an API. The API processes the request and returns a response.

You can think of an API as a messenger between two software systems.

For example, when you check the weather in a mobile application, the application does not usually store weather information itself. Instead, it sends a request to a weather service through an API. The weather service processes the request and returns current weather information, which the application displays to you.

---

# Why are APIs important?

Modern software relies heavily on APIs.

Applications use APIs to exchange information, automate tasks, and connect different services without exposing their internal implementation.

For example, APIs allow applications to:

- Process online payments.
- Display maps.
- Send emails.
- Retrieve weather information.
- Authenticate users.
- Exchange information between systems.

Without APIs, many of the applications people use every day would not be able to communicate with one another.

---

# How does an API work?

A typical API interaction follows four basic steps.

1. An application sends a request.
2. The API receives the request.
3. The API processes the request.
4. The API returns a response.

The interaction can be represented as:

```text
Application
      │
      │ Request
      ▼
     API
      │
      │ Response
      ▼
Application
```

As a Postman user, you will mainly work with requests and responses.

---

# Understanding requests

A **request** is a message sent to an API asking it to perform an action.

Common actions include:

- Retrieving information.
- Creating new information.
- Updating existing information.
- Deleting information.

A request usually contains:

- An endpoint (the destination where the request is sent).
- An HTTP method, such as GET or POST.
- Optional data.
- Optional authentication information.

The next guide explains HTTP requests and responses in more detail.

---

# Understanding responses

After receiving a request, the API returns a **response**.

A response usually includes:

- A status code indicating whether the request succeeded.
- Data returned by the API.
- Error information if the request could not be completed.

Postman allows you to inspect these responses without writing your own application.

---

# Why use Postman with APIs?

Working directly with APIs often requires writing code.

Postman provides a graphical interface that allows you to:

- Create API requests.
- Send requests to an API.
- Inspect responses.
- Test API behaviour.
- Save requests for future use.
- Organize requests into Collections.

This makes Postman a useful tool for learning APIs, testing applications, and collaborating with other developers.

---

# Key terms

| Term | Description |
|------|-------------|
| API | A set of rules that allows applications to communicate with one another. |
| Request | A message sent to an API asking it to perform an action. |
| Response | Information returned by an API after processing a request. |
| Endpoint | The destination where a request is sent. |
| HTTP Method | The action requested, such as GET or POST. |

---

# Summary

An API allows different software applications to communicate with one another.

Postman makes it easier to interact with APIs by providing tools for creating requests, inspecting responses, and organizing your work.

The concepts introduced in this guide form the foundation for the remaining documentation.

---

# Related documentation

- Previous guide: **What is Postman?**
- Next guide: **Understanding HTTP Requests and Responses**
