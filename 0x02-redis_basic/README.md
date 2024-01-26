<p align="center">
<img src ="https://logos-download.com/wp-content/uploads/2020/06/Redis_Logo.png">
</p>

---

## Redis basic:

- This project focuses on using Redis for basic operations and as a simple cache.

---

## Resources

- [Redis commands](https://redis.io/commands/)
- [Redis python client](https://redis-py.readthedocs.io/en/stable/)
- [How to Use Redis With Python](https://realpython.com/python-redis/)
- [Redis Crash Course Tutorial](https://www.youtube.com/watch?v=Hbt56gFj998)

---

## Tasks:

0. **Writing strings to Redis**

   - **Task:** Create a Cache class that uses Redis for basic operations. Implement a store method to generate a random key and store data in Redis.
   - **File:** [exercise.py](./exercise.py)

1. **Reading from Redis and recovering original type**

   - **Task:** Implement a get method in the Cache class that retrieves data from Redis, allowing optional conversion using a Callable argument. Also, add get_str and get_int methods for specific conversions.
   - **File:** [exercise.py](./exercise.py)

2. **Incrementing values**

   - **Task:** Define a count_calls decorator to count how many times methods of the Cache class are called. Decorate the store method with count_calls and demonstrate the counting functionality.
   - **File:** [exercise.py](./exercise.py)

3. **Storing lists**

   - **Task:** Implement a call_history decorator to store the history of inputs and outputs for a particular function. Decorate the store method with call_history and display the stored inputs and outputs.
   - **File:** [exercise.py](./exercise.py)

4. **Retrieving lists**
   - **Task:** Implement a replay function to display the history of calls of a particular function using keys generated in previous tasks.
   - **File:** [exercise.py](./exercise.py)

### Advanced Tasks:

5. **Implementing an expiring web cache and tracker**
    - **Task:** Implement a `get_page` function in a new file named `web.py`. The function should use the requests module to obtain the HTML content of a given URL, track the number of times the URL was accessed, and cache the result with an expiration time of 10 seconds. Bonus: Implement this use case with decorators.
    - **File:** [web.py](./web.py)

---

## Author

- [`@Josh-techie`]() | Software Engineer Student

  > Reach out to me if you need any help or have any questions.

  <a href="mailto:youssef.abouyahia@e-polytechnique.ma">
  	<img alt="Feel free to contact me" src="https://img.shields.io/badge/-Ask_me_anything-blue?style=flat&logo=Gmail&logoColor=white&link=mailto:youssef.abouyahia@e-polytechnique.ma&color=3d85c6" />
  </a>
  <span> | </span>
    <a href="https://www.linkedin.com/in/youssef-abouyahia/">
        <img alt="Linkedin Profile" src="https://img.shields.io/badge/-Linkedin-0072b1?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/youssef-abouyahia/" />
    </a>
    <span> | </span>
    <a href="https://twitter.com/JoesephAb">
        <img alt="Twitter Profile" src="https://img.shields.io/badge/-Twitter-0072b1?style=flat&logo=Twitter&logoColor=white&link=https://twitter.com/JoesephAb&color=1DA1F2" />
    </a>
