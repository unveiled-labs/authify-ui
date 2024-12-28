**Authify UI** is a lightweight and customizable React component library that provides pre-built, responsive sign-in and sign-up pages. Designed with Tailwind CSS, it enables developers to quickly integrate beautiful, user-friendly authentication interfaces into their applications. Ideal for projects requiring a seamless and modern UI for authentication workflows.

---

## Features

- **Pre-built UI Components**: Ready-to-use `SignIn` and `SignUp` components.
- **Tailwind CSS**: Fully responsive and customizable using Tailwind.
- **Ease of Integration**: Simple and straightforward API for seamless integration.
- **Modular Design**: Use only the components you need.

---

## Installation

To install the package, use the following command:

```bash
npm install authify-ui
```

Or, if you use Yarn:

```bash
yarn add authify-ui
```

---

## Usage

### Basic Example

```tsx
import React from "react";
import { SignIn, SignUp } from "authify-ui";

const App = () => {
  return (
    <div>
      <h1>Welcome to Authify UI</h1>
      <SignIn />
      <SignUp />
    </div>
  );
};

export default App;
```

---

## Components

### `SignIn`

The `SignIn` component renders a pre-designed login form.

#### Props

| Prop Name  | Type       | Description                  |
| ---------- | ---------- | ---------------------------- |
| `onSubmit` | `function` | Callback for form submission |

#### Example

```tsx
<SignIn onSubmit={(data) => console.log(data)} />
```

### `SignUp`

The `SignUp` component renders a pre-designed registration form.

#### Props

| Prop Name  | Type       | Description                  |
| ---------- | ---------- | ---------------------------- |
| `onSubmit` | `function` | Callback for form submission |

#### Example

```tsx
<SignUp onSubmit={(data) => console.log(data)} />
```

---

## Customization

### Tailwind CSS

Authify UI uses Tailwind CSS classes for styling. You can override the default styles by customizing your Tailwind configuration.

#### Example

```css
/* tailwind.config.js */
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: "#4CAF50",
      },
    },
  },
};
```

---

## Contributing

Contributions are welcome! If you’d like to contribute, please fork the repository and create a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Support

For issues and feature requests, please open a ticket on the [GitHub Issues](https://github.com/unveiled-labs/authify-ui/issues) page.

---

Happy coding! 🚀
