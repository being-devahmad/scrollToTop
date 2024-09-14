# ScrollToTop Component

This is a React component that adds a "Scroll to Top" button to your web page. The button appears when the user scrolls down the page and allows them to quickly return to the top of the page with a smooth scrolling animation.

## Features

- Appears after scrolling down 300 pixels
- Smooth scrolling animation
- Responsive design
- Customizable styling

## Usage

To use this component in your React project, simply import it and add it to your main layout or any page where you want the scroll-to-top functionality.

```jsx
import ScrollToTop from './ScrollToTop';

function App() {
  return (
    <div>
      {/* Your other components */}
      <ScrollToTop />
    </div>
  );
}
