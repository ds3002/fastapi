# API Assignment

Create an API using `FastAPI` (to run locally) that achieves the following four goals:

1. Create a GET endpoint "/test" that takes FOUR query string parameters (parameters appended to the URL such as /test?one=xxx&two=yyy&three=zzz&four=aaa) and displays them back. Two of these must be strings and two must be integers.

2. Create a POST endpoint "/items/{item_id}" that takes an "item_id" as a path parameter and a "description" in a data payload and appends them both to a text file.

3. Create a GET endpoint "/quotes/{row_number}" that takes a "row_number" parameter and returns the corresponding row (1-10) from the "quotes.txt" file included here. --> Helpful reference on extracting lines: https://www.computerhope.com/issues/ch001721.htm

4. Create a GET endpoint "/github/{username}" that retrieves and returns the URL of the specified user's Github profile picture and returns it. --> Github User API reference: https://docs.github.com/en/rest/reference/users

FastAPI Documentation: https://fastapi.tiangolo.com/