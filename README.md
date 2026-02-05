# Hello 👋🏼

**Who?**  
Hi, I'm Martin Johannes Nilsen, a Norwegian Software Engineer. If you'd like to know more about me, check out [my very first blog post](https://blog.mjnlab.com/posts/hello-im-martin).

**What?**  
This project is my personal technology and development blog, where I write about topics like 💻 Technology, 👨🏼‍💻 Programming, 🏠 Home Automation, and other related areas. The goal is to keep it simple, fast, and informative, whether you're into deep technical reads or casual browsing.

**How?**  
The site is built with Next.js 15, using the App Router architecture for a modern and stable foundation. All frontend code is written in TypeScript, ensuring maintainability and type safety. I previously used MUI (Material UI) for the UI layer but migrated to Tailwind CSS and shadcn for leaner bundles, faster performance, and a consistent design system without emotion/JSS runtime overhead. The result is a noticeably snappier user experience.

Initial versions used Firebase and Supabase for persistence, which are great choices for early development. Later, I moved to self-hosted Docker containers with MongoDB and mongo-express for easier migration. Finally, I transitioned to PostgreSQL, which now serves as the main data layer for robustness and scalability.

**Today (v4)**  
Version 4 represents a major leap forward: a technology blog with a built-in CMS, featuring:

- Next.js 15 server and client rendering with on-demand cache revalidation, where writers decide when to publish and revalidate, while drafts stay in the database
- Notion-styled Editor.js editor with custom-designed block tools for a refined writing and editing experience
- Fully managed authentication for administrators and reviewers
- View counts stored in PostgreSQL
- API with administrator-controlled token management
- In-browser local notifications
- Design system overview page for visual consistency
- and ongoing improvements and optimizations

**Ready to explore?**  
⚡️ [Visit the landing page](https://blog.mjnlab.com)
