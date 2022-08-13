This is a starter template for [Learn Next.js](https://nextjs.org/learn).

Create Directories and Files:
# Components
- - layout.js
import styles from './layout.module.css';

export default function Layout({ children }) {
  return <div className={styles.container}>{children}</div>;
}

- - layout.module.css (adds CSS to the Layout Component)
.container {
  max-width: 36rem;
  padding: 0 1rem;
  margin: 3rem auto 6rem;
}
# styles
In Next.js, you can add global CSS files by importing them from pages/_app.js. You cannot import global CSS anywhere else.
- global.css
- utils.module.css