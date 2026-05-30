# healthvc
Health query and GP medical note experimental app hosted on vercel

## A healthcare application that:
- Takes doctor's consultation notes as input
- Generates professional summaries for medical records
- Creates actionable next steps for the doctor
- Drafts patient-friendly email communications
- Uses structured forms with date pickers
- Streams AI-generated content in real-time

Enhancements Due:
 - Add ability to search for any sympotms with brief details
 - Most suitable over the counter medicine or tablets available in user's country
 - Add email capability (using sendGrid or something)

vercel commands

- vercel login
- vercel link (upload existing project to new project on vercel)

Add environment variable used in the app ( select Production and Preview env only using space bar)

- vercel env add OPENAI_API_KEY
- vercel env add NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY
- vercel env add CLERK_SECRET_KEY
- vercel env add CLERK_JWKS_URL

Deployment to Production

- vercel --prod