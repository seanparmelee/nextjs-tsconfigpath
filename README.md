This is a [Next.js](https://nextjs.org/) template to use when reporting a [bug in the Next.js repository](https://github.com/vercel/next.js/issues) with the `app/` directory.

# Steps to Reproduce
1. Run `npm run dev:turbo`
2. Navigate to http://localhost:3000/
3. You should see the error `Module not found: Can't resolve '@/components/Hello'`
4. Terminate the server
5. Run `npm run dev`
6. Navigate to http://localhost:3000/
7. Confirm the page renders successfully
