- localtunnel.x.domain.com
- domain.com/x/short-url (optional top-level)
- file uploads (leverage short urls for domain.com/x/jaskdh.png)


1. ssh tunelling
  - `localtunnel.x.domain.com`
2. short urls
  - `domain.com/x/short-url-code` (with option to be top-level without `/x`; but the application hosted there would need to talk to sharex)
3. file uploads
  - upload to configured CDN, or just to disk.
  - leverages short urls for `domain.com/x/resume.pdf`
4. tracking
  - short links can enable tracking
  - ssh tunneled apps can use tracking
  - HTML and JS code snippets can be generated for tracking
    - images that track a visit when loaded
    - script that does a fetch request (likely problematic with cors)
  - discord webhooks
5. 

