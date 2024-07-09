# Accessible Astro Starter for Typescript

A fork of [Mark Teekman](https://github.com/markteekman)'s [Accessible Astro Starter](https://github.com/markteekman/accessible-astro-starter) theme, with support added for strict Typescript.

![social-preview-image](https://user-images.githubusercontent.com/3909046/219942674-9894853e-def8-4180-84b8-6b577dacfcaa.png)

Accessible Astro Starter is a ready to use, SEO and a11y friendly blogging theme. It contains plenty of accessible components to build several page types, Tailwind CSS to help you build faster and example pages such as a dynamic Blog, 404, Markdown and MDX. This theme is designed to help you build your project faster and provide a solid base for accessibility!

🚀 [Live Preview](https://accessible-astro.netlify.app/)

## ♿ (Accessibility) Features

- Astro 4.0
- Tailwind CSS support
- Prettier integration with `prettier-plugin-astro` and `prettier-plugin-tailwind`
- ESLint integration with strict accessibility settings for `eslint-plugin-jsx-a11y`
- Markdown and MDX support with examples included in the theme
- Uses the awesome `astro-icon` package for the icons
- Excellent Lighthouse/PageSpeed scores
- Accessible landmarks such as `header`, `main`, `footer`, `section` and `nav`
- Outline focus indicator which works on dark and light backgrounds
- Several `aria` attributes which provide a better experience for screen reader users
- `[...page].astro` and `[post].astro` demonstrate the use of dynamic routes and provide a basic blog with breadcrumbs and pagination
- `404.astro` provides a custom 404 error page which you can adjust to your needs
- `Header.astro` component included in the `DefaultLayout.astro` layout
- `Footer.astro` component included in the `DefaultLayout.astro` layout
- `SkipLinks.astro` component to skip to either the main menu or the main content
- `Navigation.astro` component with keyboard accessible (dropdown) navigation (arrow keys, escape key)
- `ResponsiveToggle.astro` component with an accessible responsive toggle button for the mobile navigation
- `DarkMode.astro` component toggle with accessible button and a user system preferred color scheme setting
- `SiteMeta.astro` SEO component for setting custom meta data on different pages
- `.sr-only` utility class for screen reader only text content (hides text visually)
- `prefers-reduced-motion` disables animations for users that have this preference turned on
- Ships with many components such as Accordions, Breadcrumbs, Modals, Pagination [and many more](https://accessible-astro.dev/accessible-components)
- A collection of utility classes such as breakpoints, button classes, font settings, resets and outlines in `src/assets/scss/base`
- View Transitions (⚠️ see [astro-docs](https://docs.astro.build/en/guides/view-transitions/#accessibility) for accessibility considerations)

## 🚀 Getting started

Create a new Astro project by either:
- cloning this repository:
   ```
   git clone https://github.com/mrivard/accessible-astro-starter-ts.git
   ```
*&ndash;or&ndash;*
- using this repository as your project's template:
   ```
   npm create astro@latest -- --template mrivard/accessible-astro-starter-ts
   ```

Then, run any of the following commands in your project's directory:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:4321`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## 📦 Other Accessible Astro projects

- [Accessible Astro Dashboard](https://github.com/markteekman/accessible-astro-dashboard/)
- [Accessible Astro Components](https://github.com/markteekman/accessible-astro-components/)

## ❤️ Helping out

I would love for you to help with any Typescript-related issues by either:

1. [Filing an issue](https://github.com/mrivard/accessible-astro-starter-ts/issues)
2. [Submitting a pull request](https://github.com/mrivard/accessible-astro-starter-ts/pulls)
3. [Starting a discussion](https://github.com/mrivard/accessible-astro-starter-ts/discussions)

For any issues that are *not* Typescript-related, you would be much better served by engaging with [Accessible Astro Starter](https://github.com/markteekman/accessible-astro-starter?tab=readme-ov-file#%EF%B8%8F-helping-out) instead.

## ☕ Thank you!

A big thank you to [Mark Teekman](https://github.com/markteekman) and his [contributors](https://github.com/markteekman/accessible-astro-starter/graphs/contributors), who did 99.999% of the work on this theme, and to the creators of the awesome Astro static site generator. I forked Mark's theme for my own personal use, and perhaps you will find it useful as well.

