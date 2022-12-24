# Rest API - Golang

## Model
- Notes
    ```json
    {
        "id": 123,
	    "title": "Golang",
	    "body" : "Golang adalah bahasa yang dibuat oleh google",
    }
    ```

# Endpoint
## Create Note
- URL : `localhost:8080/api/v1/notes`
- Method: `POST`
- request body
    ```json
    {
        "title": "Golang",
	    "body" : "Golang adalah bahasa yang dibuat oleh google",
    }
    ```
- response
    ```json
    {
        "code": "201",
	    "status": "Success",
	    "message" : "Note Baru Berhasil Ditambahkan",
    }
    ```