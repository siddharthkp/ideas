
### API snapshot testing

- A test = request URL + data (json?)
    {
        "method": "GET",
        "url": "https://npm-janitor-api.now.sh",
        "data": {
            "user": "siddharthkp"
        }
    }

- Generate actual tests for each json object (abstracted from user)
- Store response in a snapshot
- Watch mode with the API code (need not be javascript)
- Update screenshots when happy with changes
- Running tests in parallel? Real API calls = slow


