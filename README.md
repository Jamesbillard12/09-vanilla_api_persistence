# Vanilla API Persistence - 09 Lab

## Description:
This app builds out an API where data is stored in the file system. This API stores beer data with the schema of name, style, and IBU.

## API:
The URL endpoint to access the api is `/api/beer`.  Using REST architecture the data is read, written and deleted using `GET`, `POST` and `DELETE` requests.

###POST:

```
request.post('localhost:8000/api/beer')
.send({ name: 'Have a Nice Day IPA', style: 'IPA', IBU: '43' })
```

This is a representation of the post method. You can see that we first make a request to post to
```
localhost:8000
```
with a route of
```
/api/beer.
```
Once the connection has bee made we send our beer in
```
.send({ name: 'Have a Nice Day IPA', style: 'IPA', IBU: '43' })
```
format.
