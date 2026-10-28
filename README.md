# epls-r-users

R user group at Florida State University (EPLS), mostly announcements

Automated mbox archive. Updated daily via GitHub Actions.

## Structure

- `raw/` - Monthly .mbox files downloaded from [https://lists.fsu.edu/pipermail/epls-r-users/](https://lists.fsu.edu/pipermail/epls-r-users/)
- `processed/` - Structured JSON output from rmail-parser
- `sources/` - Where present, each message's page at the source and the characters that page restores, one JSON file per period
- `attachments/` - Text Mailman scrubbed out of messages, fetched once from the source and put back by rmail-parser, one gzip-compressed JSON file per period
- `meta.json` - List statistics

## Viewer

Browse these archives at [r-mailing-lists.thecoatlessprofessor.com](https://r-mailing-lists.thecoatlessprofessor.com/lists/epls-r-users/)
