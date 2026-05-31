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

### Potential Enhancements

1. **Template library**: Pre-built templates for common conditions
2. **Voice input**: Dictation support for notes
3. **Multi-language**: Support for patient emails in different languages
4. **Integration**: Connect with EHR systems
5. **Analytics**: Track consultation patterns and time saved
6. **Collaboration**: Allow multiple doctors to share templates

## Security Considerations

**Important:** This is a demonstration application. For production healthcare use:
- Implement proper HIPAA compliance measures
- Add data encryption at rest and in transit
- Implement audit logging for all access
- Add role-based access control (doctor vs admin)
- Ensure proper data retention policies
- Add patient consent management


## vercel commands

- vercel login
- vercel link (upload existing project to new project on vercel)

Add environment variable used in the app ( select Production and Preview env only using space bar)

- vercel env add OPENAI_API_KEY
- vercel env add NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY
- vercel env add CLERK_SECRET_KEY
- vercel env add CLERK_JWKS_URL

Deployment to Production

- vercel --prod