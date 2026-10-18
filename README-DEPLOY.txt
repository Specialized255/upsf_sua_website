UPSF WEBSITE — NETLIFY DEPLOYMENT

1. Extract upsf-netlify-site.zip on your phone/computer.
2. Open https://app.netlify.com/ and sign in or create an account.
3. In Netlify, choose Add new site / Deploy manually (the wording may vary).
4. Drag and drop the extracted folder named upsf-netlify-site, or drag its contents including index.html and assets.
5. Wait for the deploy to finish. Netlify will give you a public URL ending in netlify.app.
6. To change the URL, open Site configuration / Domain management and edit the site name if available.

IMPORTANT — REGISTRATION FORM
- After the first deployment, open the site in Netlify and check Forms. Ensure form detection is enabled if prompted, then trigger a new deploy.
- Submit a test registration and confirm it appears under Forms / submissions.
- File uploads and form handling depend on your Netlify plan and current form configuration. Check the dashboard after testing.
- This static site does not yet include a private member/admin dashboard or a Supabase database. Do not treat it as a complete protected membership records system until that is built.
