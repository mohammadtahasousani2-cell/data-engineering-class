\# Activity 5: Test Cases



| # | Scenario | Request | Expected result |

|---|---|---|---|

| 1 | List users | `GET /users` | `200 OK` with a list of users |

| 2 | Create a valid user | `POST /users` with valid `name` and `email` | `201 Created` with the new user |

| 3 | Create a user without email | `POST /users` with `name` but no `email` | `400 Bad Request` with a validation error |

| 4 | Fetch a nonexistent user | `GET /users/999999` | `404 Not Found` |

| 5 | Create a valid task | `POST /tasks` with a valid `title` | `201 Created` with the new task |



> These are planned API test cases; they describe expected behavior and do not run tests against a live API.



