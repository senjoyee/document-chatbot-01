# document-chatbot-01
For chatting with documents with advanced features
# Frontend Chatbot Component

This project is a Next.js application featuring a chatbot component. Follow the instructions below to set up and run the project.

## Prerequisites

- Node.js (latest LTS version recommended)
- npm (comes with Node.js)

## Setup Instructions

1. Create a new Next.js project:

   ```
   npx create-next-app@latest frontend
   ```

   When prompted, choose the following options:
   - Use TypeScript: Yes
   - Use ESLint: Yes
   - Use Tailwind CSS: Yes
   - Use `src/` directory: Yes
   - Use App Router: Yes
   - Customize the default import alias: No

2. Navigate to the project directory:

   ```
   cd frontend
   ```

3. Install additional dependencies:

   ```
   npm install lucide-react @radix-ui/react-scroll-area
   npm install react-dropzone lucide-react sonner
   ```

4. Set up the shadcn/ui components:
   
   ```
   npx install shadcn
   ```

   ```
   npx shadcn@latest init
   ```

   
6. Add the required shadcn/ui components:

   ```
   npx shadcn@latest add button input scroll-area card table checkbox
   ```

7. Create a new file for the chatbot components:

   create a file `chatbot.tsx` under src\components and update the code accordingly.

   create a file `uploadservice.tsx` under src\components and update the code accordingly.

8. Open `src/components/chatbot.tsx` in your code editor and paste the chatbot component code.
   
10. Open `src/components/uploadservice.tsx` in your code editor and paste the uploadservice component code.

11. Place the logo file `SoftwareOne_Logo_Lrg_RGB_Blk.svg` in the `public` folder of your Next.js project. Create the folder if it's missing.

12. Update `src/app/page.tsx` to use the Welcome Page.

13. Create `src/app/chatbot/page.tsx` and update it.

14. Create `src/app/uploadservice/page.tsx` and update it.

15. Ensure that the latest Avatar component from Shadcn is available;

    ```
    npx shadcn@latest add avatar
    ```
    
16. Start the development server:

    ```
    npm run dev
    ```

## Project Structure

- `src/components/Chatbot.tsx`: Contains the main chatbot component
- `src/components/uploadservice.tsx`: Contains the uploadservice component
- `src/app/page.tsx`: Main page component that uses the Chatbot
- `public/SoftwareOne_Logo_Lrg_RGB_Blk.svg`: Logo file for the chatbot

## Dependencies

- Next.js
- React
- TypeScript
- Tailwind CSS
- lucide-react
- @radix-ui/react-scroll-area
- shadcn/ui components (button, input, scroll-area)

## Development

After setting up the project, you can start developing by modifying the `Chatbot.tsx` and the `uploadservice` component or adding new components as needed. The development server will automatically reload when you make changes to the code.

## Building for Production

To create a production build, run:

```
npm run build
```

This will generate an optimized version of your application in the `.next` folder.

## Deployment

Follow the Next.js deployment documentation to deploy your application to your preferred hosting platform.

## License

[MIT License](https://opensource.org/licenses/MIT)
