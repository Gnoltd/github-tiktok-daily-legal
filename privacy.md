# Privacy Policy

Last updated: 2 November 2026

This policy describes how the application "Gnoltd" (also called github-tiktok-daily), operated by the GitHub user Gnoltd ("the Operator"), handles data.

## 1. Whose data

The application is a personal tool. It is authorized only by the Operator's own TikTok account. It does not offer login to anyone else and does not collect personal data from any other TikTok user or visitor.

## 2. What is accessed

When the Operator authorizes the application, TikTok provides an access token, a refresh token and the Operator's TikTok open ID, together with the permissions the Operator granted (`user.info.basic` and `video.upload`). The application does not read the Operator's profile, videos, followers or messages.

## 3. How it is used

The tokens are used only to upload the daily draft video to the Operator's own TikTok account. Nothing else is done with them.

## 4. Where it is stored

The tokens are stored as encrypted secrets in a private GitHub repository owned by the Operator. They are not published, sold or shared with anyone.

## 5. Third parties

The video script is produced from public GitHub information using automated tools, including Google Gemini. No TikTok account data is sent to Google or to any other third party for that purpose. GitHub hosts the private repository that holds the encrypted tokens (section 4) and runs the scheduled job.

## 6. Retention and revocation

Tokens are kept until the Operator revokes them. The Operator can revoke access at any time in TikTok under Settings and privacy, Security and permissions, Apps and services. Deleting the GitHub secrets also removes the stored tokens.

## 7. Changes

The Operator may update this policy at any time. The date above shows the latest revision.

## 8. Contact

Open an issue at https://github.com/Gnoltd/github-tiktok-daily-legal/issues
