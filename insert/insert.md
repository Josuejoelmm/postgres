```postgres
INSERT INTO photos (url, user_id)
VALUES ('http://img-1.jpg', 3);
```

For multiple rows:

```postgres
INSERT INTO photos (url, user_id)
VALUES
	('http://pic1.jpg', 4),
	('http://pic2.jpg', 4),
	('http://pic3.jpg', 1),
	('http://pic4.jpg', 2);
```