### Vite - Build Tools

**Purpose:** Vite was created to address the performance challenges of traditional bundler tools, which slow down as JavaScript applications scale. It leverages advances in native ES modules in browsers and low-level language compilation tools to accelerate development server startup times and provide instant code updates. This approach allows developers to achieve significantly faster feedback cycles, regardless of project size.

**Documentation:** https://vite.dev/guide/why.html

**Workflow:** Vite splits the development workflow by providing an instant Native ESM-based development server for day-to-day coding, while still using an optimized bundler (Rollup) when building applications for production.

### Vitest - Testing Frameworks

**Purpose:** Developers use Vitest because it provides a "Vite-native" testing experience, allowing them to share the same configuration and transformation pipeline across development, build, and test environments. It offers a fast, modern alternative to Jest with built-in support for features like HMR, worker threads for parallelism, and a compatible API that makes it easy to migrate existing projects.

**Documentation:** https://vitest.dev/guide/why

**Workflow:** Vitest integrates into the development process as a fast, watch-mode-oriented test runner that uses the same configuration as the application, ensuring that tests run in an environment that perfectly matches the development and build pipelines.

### Figma - Design Tool

**Purpose:** Figma is a cloud-based interface design tool used by teams to build wireframes, high-fidelity mockups, and interactive prototypes for web and mobile applications. It solves the problem of "design-to-code" friction by allowing designers and developers to collaborate in real-time within a single document, eliminating the need for constant file exports or version control confusion. Developers use it specifically to inspect design properties—such as CSS, spacing, and assets—ensuring the final product matches the original vision perfectly.

**Documentation:** https://help.figma.com/hc/en-us

**Workflow:** Figma serves as the "source of truth" during the handoff phase, where developers use Dev Mode to translate visual designs directly into technical specifications and production-ready assets.

