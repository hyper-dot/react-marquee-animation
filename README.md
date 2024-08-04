# react-marquee-animation

A React component for creating smooth and customizable marquee animations, perfect for infinite scroll, carousels, tickers, and horizontal scrolling animations.

## Features

- Smooth scrolling animations
- Easy to integrate and customize
- Supports infinite scroll
- Lightweight and fast
- Written in TypeScript

## Installation

Install the package using npm or yarn:

```bash
npm install react-marquee-animation
```

or

```bash
yarn add react-marquee-animation
```

## Usage

Here's a basic example of how to use the `react-marquee-animation` component in your React application:

```tsx
import React from 'react';
import Marquee from 'react-marquee-animation';

const App: React.FC = () => {
  return (
    <div>
      <Marquee>
        <div>Your content here</div>
        <div>Another content</div>
        <div>More content</div>
      </Marquee>
    </div>
  );
};

export default App;
```

## Props

The `Marquee` component supports the following props:

| Prop             | Type     | Default      | Description                                          |
|------------------|----------|--------------|------------------------------------------------------|
| `speed`          | number   | 50           | The speed of the marquee animation.                  |
| `direction`      | string   | 'left'       | The direction of the marquee ('left' or 'right').    |
| `pauseOnHover`   | boolean  | false        | Pause the animation when hovered.                    |
| `loop`           | boolean  | true         | Whether the marquee should loop indefinitely.        |
| `children`       | ReactNode| N/A          | The content to be animated in the marquee.           |

## Development

To contribute to the project or run it locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/hyper-dot/react-marquee-animation.git
    ```
2. Install dependencies:
    ```bash
    cd react-marquee-animation
    npm install
    ```
3. Run the development server:
    ```bash
    npm run dev
    ```

## Building the package

To build the package for production:

```bash
npm run build
```

## Linting

To lint the project:

```bash
npm run lint
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Author

Roshan Paudel

For any inquiries or issues, please contact [rozanpoudel@gmail.com](mailto:rozanpoudel@gmail.com).

## Repository

For more details, please visit the [GitHub repository](https://github.com/hyper-dot/react-marquee-animation).
