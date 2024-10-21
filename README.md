Create a bounty form boilerplate that uploads the submissions to Arweave.

Requirements:
- Must have the tags below for easier querying
- Must be able to fetch the submissions

Must have the tags:
- name: "arweaveph-bounty"
- date: <date of submission>
- submitted_by: <who submitted>
- link: <link to submission>
- wallet_address: <submitted wallet>
- additional_info: <must accept a JSON string>

Must use the following technologies:
- Turbo-SDK: @ardrive/turbo-sdk
- Next.js 13 or up (App router)

References:
- https://cookbook.arweave.dev/guides/posting-transactions/turbo.html

Bonus points:
- A way to query the submissions using a particular tag/s
- Build it on AO computer so all submissions are saved on a particular process. Make sure to have a way to both save and fetch.