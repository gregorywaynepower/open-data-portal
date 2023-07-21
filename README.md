# Cary's Open Data Portal

## Opendatasoft & Bootstrap

- Opendatasoft uses [Bootstrap](https://discovery.opendatasoft.com/pages/concept-responsive/)-like classes for layout configuration.
- Version of Bootstrap may change, [here is a more comprehensive source of documentation](https://getbootstrap.com/docs/4.0/layout/overview/)
- For their visualizations, there is the [ods-widgets](https://github.com/opendatasoft/ods-widgets)
- Additional dependencies and libraries they import for their charts, they use [Highcharts JS v6.1.4](https://www.highcharts.com/blog/changelog/#highcharts-stock-v6.1.4) in our theme.

## Accessibility

- MDN's [Documentation on Accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility)

## Ad Hoc Styling Standards

### Headings

#### `html` Tag

Provides a default standard text size for the HTML document.

```css
html {
  font-size: 16px;
}
```

#### `h1` Heading

The following styles will be implemented:

```css
h1 {
  color: #003e7a !important;
  font-size: 2rem;
  line-height: 1.25;
  font-family: "Poppins", sans-serif;
  font-weight: 400;
  text-align: center;
  text-transform: none;
}
```

#### `h2` Heading

The following styles will be implemented:

```css
h2 {
  color: #ffffff;
  background-color: #003e7a;
  font-size: 1.5rem;
  line-height: 1.25;
  font-family: "Poppins", sans-serif;
  font-weight: 400;
  text-align: center;
  text-transform: none;
}
```

#### `h3` Heading

The following styles will be implemented:

```css
h3 {
  color: #ffffff;
  background-color: #003e7a;
  font-size: 1.5rem;
  line-height: 1.17;
  font-family: "Poppins", sans-serif;
  font-weight: 400;
  text-align: center;
  text-transform: none;
}
```

#### `h4` Heading

The following styles will be implemented:

```css
h4 {
  color: #ffffff;
  background-color: #003e7a;
  font-size: 1rem;
  line-height: 1.17;
  font-family: "Poppins", sans-serif;
  font-weight: 400;
  text-align: center;
  text-transform: none;
}
```

#### `h5` Heading

The following styles will be implemented:

```css
h5 {
  color: #ffffff;
  background-color: #003e7a;
  font-size: 0.83rem;
  line-height: 1.17;
  font-family: "Poppins", sans-serif;
  font-weight: 400;
  text-align: center;
  text-transform: none;
}
```

#### `h6` Heading

The following styles will be implemented:

```css
h6 {
  color: #ffffff;
  background-color: #003e7a;
  font-size: 0.67rem;
  line-height: 1.17;
  font-family: "Poppins", sans-serif;
  font-weight: 400;
  text-align: center;
  text-transform: none;
}
```

### Body Text

#### `<p>` Paragraph Text

```css
p {
  font-family: "Poppins", sans-serif;
  color: #4d4d4d;
}
```