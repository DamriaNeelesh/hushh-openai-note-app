**HUSHH.ai: AI Bot Note taking application project
Tech Stakc used : Nextjs, ChatGPT Api, Tailwind CSS, Vector Embeddings, Shadcn UI, TypeScript, MondoDB**

**Features:**
AI-Powered Chatbot: Engage in real-time conversations with our AI chatbot, ask questions about your notes, and receive insightful answers.

Intelligent Document Retrieval: Seamlessly retrieve relevant documents and notes using ChatGPT vector embeddings and Pinecone.

Personalized User Experience: Switch between light and dark themes for optimal viewing comfort with our next-themes integration.

Secure User Authentication: Protect your notes with Clerk's robust authentication system, ensuring only authorized users can access your information.

CRUD Operations for Notes: Create, update, and delete notes effortlessly using Prisma and MongoDB Atlas, maintaining a well-organized note-taking system.

Organized Layouts: Navigate through structured and intuitive layouts, thanks to our nested layouts implementation.

Comprehensive Form Validation: Validate form inputs both client-side and server-side with Zod, React-Hook-Form, and Shadcn UI Form, ensuring data integrity.

Fully Responsive Design: Experience a seamless user experience across all devices with our TailwindCSS modifiers, ensuring the app adapts perfectly to any screen size.


**Technology Stack**
Next.js 14: A modern React framework for building server-side rendered applications.

ChatGPT API: Leverage the power of ChatGPT to generate human-quality text, translate languages, write different kinds of creative content, and answer your questions in an informative way.

Vector Embeddings: Represent text documents as vectors in a high-dimensional space, enabling efficient similarity searches and document retrieval.

Pinecone: A scalable vector similarity search engine for rapid and accurate document retrieval.

TailwindCSS: A utility-first CSS framework for building responsive and customizable user interfaces.

Shadcn UI: A collection of React components for building beautiful and accessible user interfaces.

TypeScript: A superset of JavaScript that adds type annotations, ensuring code reliability and maintainability.

Vercel AI SDK: A suite of tools for integrating AI capabilities into your Next.js applications.

API Route Handlers: Create and handle API routes to communicate with your application's backend.

Clerk: A user authentication and authorization platform for securing your application.

Prisma: A powerful data modeling and manipulation tool for interacting with your database.

MongoDB Atlas: A cloud-based NoSQL database for storing your notes and application data.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

Please update the .env file properly with your own ChatGPT Api key and mongoDb setup

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
