# Personal CRM

<aside>
💡 **Notion Tip:** Keep track of all the people you meet, what you know about them, when to reach out and say hello, and whether they're a professional contact. You can expand the table below into a full page by clicking `⤢`.

</aside>

[Contacts](Personal%20C%2021c5e/Contacts%20760a7.csv)

## How this template works

You can delete this once you get the hang of it!

---

**We used this formula in the `Status` column of the table above.**

```jsx
if(dateBetween(now(), prop("Last Spoke"), "months") > 3, "Time to reach out!", "👍")
```

If more than 3 months have passed since the last time you contacted the person, you'll see **"Time to reach out!"** appear next to their name. 

- Edit the number 3 to change the time range for outreach.
- Change the message that appears by editing "Time to reach out!" or the "👍"

## Other cool things about this CRM

---

- Click `All Contacts` at the top left of your table to view your people different ways — like just your professional contacts, or just your college friends.
- Hover over anyone's name and click `⤢ OPEN` to open an entire page about them where you can store their address, favorite dessert 🍰, or any other relevant info!