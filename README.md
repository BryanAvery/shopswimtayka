
# Dynamic Iframe URL Loader

This project provides a simple yet powerful solution for dynamically loading URLs into an iframe based on query parameters. It is ideal for websites needing to embed different pages or product categories seamlessly within a single iframe. The current implementation is tailored to work with URLs prefixed with `https://tailoredforyou.co.uk/`, but it can be easily adapted to other bases.

## Features

- **Dynamic URL Loading**: Dynamically adjust the iframe's `src` attribute based on the presence of a `path` query parameter.
- **Default URL Fallback**: Automatically fallback to a default URL if no specific path is provided.
- **Robust URL Handling**: Utilizes JavaScript's `URL` and `URLSearchParams` for reliable parsing and handling of URLs.

## Getting Started

To get started with this project, simply clone this repository to your local machine.

```bash
git clone [https://github.com/yourusername](https://github.com/BryanAvery/shopswimtayka.git
```

Open the `index.html` in any modern web browser to see the functionality in action.

## Usage

Navigate to the `index.html` page and append a `path` query string to the URL to dynamically change the iframe's content. For example:

```plaintext
index.html?path=product-category/new-swimsuits
```

This will load the content from `https://tailoredforyou.co.uk/product-category/new-swimsuits` into the iframe. If no path is provided, it defaults to:

```plaintext
https://tailoredforyou.co.uk/product-category/swim-tayka
```

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

