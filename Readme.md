# fakeIt.JS
### A basic JS library that generates fake data

##Getting Started

Simply download or clone this repo and reference the `fakeIt.js` from your html file.

**Example:**

```
<!DOCTYPE html>
<html lang="en">
  <head></head>
  <body>
    <script src="fakeIt.js"></script>
  </body>
</html>
```

## Usage
In order to generate fake data all you need to do is to add `data-faker` attribute to your html tags. 

**Example**

```
First Name: <span class="lead" data-faker="firstName"></span>
```

would be rendered as

```
First Name: Jolien
```

```
Last Name: <span class="lead" data-faker="lastName"></span>
```

would be rendered as

```
Last Name: Grasse
```

Each time page is refreshed new random data will be generated.

## Supported Data Types

```
firstName - lastName - fullName - email - paragraph
```

## Example Usage

```
	First Name: <p data-faker="firstName"></p>
  	Last Name: <span data-faker="lastName"></span>
	Full Name: <div data-faker="fullName"></div>
  	Email: <font data-faker="email"></font>
  	Paragraph: <span data-faker="paragraph 1"></span>

```

* `**data-faker="firstName"**` 	generates a random first name

* `**data-faker="lastName"**` 	generates a random last name

* `**data-faker="fullName"**` 	generates a random first and last name

* `**data-faker="email"**` 	generates a random email

* `**data-faker="paragraph 1"**` generates a 1 lorem paragraph

* `**data-faker="paragraph n"**` generates n times lorem paragraph

## License

fakeIt.JS is licensed under the MIT License.

## Contributing

Contributions welcome! Please contact using GitHub
