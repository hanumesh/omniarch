# omniarch
https://omniarch.lovable.app/
OmniArch is built as a Full-Stack AI-Native Web Application.It follows a modern, serverless, and event-driven architecture designed for rapid scaling and real-time interaction


1. Technical Architecture
OmniArch is built as a Full-Stack AI-Native Web Application. Since it was developed using the Lovable platform, it follows a modern, serverless, and event-driven architecture designed for rapid scaling and real-time interaction.

Frontend (The Presentation Layer):

Framework: React with TypeScript for a robust, type-safe user interface.

Build Tool: Vite, ensuring near-instant hot module replacement (HMR) for a smooth development experience.

Styling: Tailwind CSS combined with shadcn/ui components. This allows for a highly responsive, "Figma-like" visual editing experience.

State Management: Utilizes TanStack Query (React Query) for efficient data fetching, caching, and synchronization with the backend.

Backend & Data (The Infrastructure Layer):

BaaS (Backend-as-a-Service): Powered by Supabase.

Database: PostgreSQL for structured data storage (e.g., project metadata, user profiles).

Authentication: Supabase Auth handles secure social logins and session management.

Storage: Supabase Storage for hosting high-resolution architectural assets and user-uploaded files.

AI & Logic (The Intelligence Layer):

AI Gateway: Connects the frontend to Large Language Models (LLMs) like Gemini 1.5 Flash. This enables the "prompt-to-design" capabilities where natural language is translated into UI changes or architectural configurations.

Edge Functions: Serverless logic that runs close to the user, handling API integrations and complex data processing without a traditional dedicated server.

2. LinkedIn Post Draft
Option: The "Problem vs. Solution" Hook

Headline: Why settle for static blueprints when you can walk through your vision? 🏗️✨

I’m excited to share a project I’ve been working on: OmniArch.

Traditional architectural visualization often feels "stuck"—static renders and rigid camera paths don't capture the true feeling of a space. OmniArch changes that by bridging the gap between professional ArchViz and immersive, real-time exploration.

Key Features:
🔹 First-Person Exploration: Move through environments freely to experience scale and atmosphere as if you were there.
🔹 Real-Time Configuration: Instantly swap materials and lighting to see how design choices impact the space.
🔹 AI-Powered Workflow: Built using a cutting-edge stack (React, Supabase, and Gemini) to turn complex concepts into interactive experiences in record time.

Whether you're an architect looking to wow clients or a designer seeking faster iteration, OmniArch is built to bring your ideas to life.

Check out the live app here: https://omniarch.lovable.app/1. Technical Architecture
OmniArch is built as a Full-Stack AI-Native Web Application. Since it was developed using the Lovable platform, it follows a modern, serverless, and event-driven architecture designed for rapid scaling and real-time interaction.

Frontend (The Presentation Layer):

Framework: React with TypeScript for a robust, type-safe user interface.

Build Tool: Vite, ensuring near-instant hot module replacement (HMR) for a smooth development experience.

Styling: Tailwind CSS combined with shadcn/ui components. This allows for a highly responsive, "Figma-like" visual editing experience.

State Management: Utilizes TanStack Query (React Query) for efficient data fetching, caching, and synchronization with the backend.

Backend & Data (The Infrastructure Layer):

BaaS (Backend-as-a-Service): Powered by Supabase.

Database: PostgreSQL for structured data storage (e.g., project metadata, user profiles).

Authentication: Supabase Auth handles secure social logins and session management.

Storage: Supabase Storage for hosting high-resolution architectural assets and user-uploaded files.

AI & Logic (The Intelligence Layer):

AI Gateway: Connects the frontend to Large Language Models (LLMs) like Gemini 1.5 Flash. This enables the "prompt-to-design" capabilities where natural language is translated into UI changes or architectural configurations.

Edge Functions: Serverless logic that runs close to the user, handling API integrations and complex data processing without a traditional dedicated server.

2. LinkedIn Post Draft
Option: The "Problem vs. Solution" Hook

Headline: Why settle for static blueprints when you can walk through your vision? 🏗️✨

I’m excited to share a project I’ve been working on: OmniArch.

Traditional architectural visualization often feels "stuck"—static renders and rigid camera paths don't capture the true feeling of a space. OmniArch changes that by bridging the gap between professional ArchViz and immersive, real-time exploration.

Key Features:
🔹 First-Person Exploration: Move through environments freely to experience scale and atmosphere as if you were there.
🔹 Real-Time Configuration: Instantly swap materials and lighting to see how design choices impact the space.
🔹 AI-Powered Workflow: Built using a cutting-edge stack (React, Supabase, and Gemini) to turn complex concepts into interactive experiences in record time.

Whether you're an architect looking to wow clients or a designer seeking faster iteration, OmniArch is built to bring your ideas to life.

Check out the live app here: https://omniarch.lovable.app/



Recommended Replacement Models
Based on your original architecture's need for "high-context orchestration", here are the best current alternatives available on Groq:

llama-3.3-70b-specdec: This is the direct successor for high-performance reasoning and large context tasks. It is highly recommended for the multi-domain agent orchestration your app performs.

llama-3.1-8b-instant: Use this if you want maximum speed and lower latency, though it may be slightly less "smart" at complex cross-domain synthesis.


llama-3.2-11b-vision-preview: If you still intend to use the image upload features of your UI, you must use this model, as the standard Llama 3.1/3.3 models are text-only.

Reminder on Connection Issues
If you still see errors after updating the model name:


CORS: Ensure you aren't trying to call the API directly from a local file:// path in your browser, as Groq's security policy will block it. You should ideally use a local development server or a proxy.


API Key: Verify that YOUR_GROQ_API_KEY has been replaced with a valid key from your Groq Console.
