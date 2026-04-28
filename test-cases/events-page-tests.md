# Тест-кейси для сторінки подій GreenCity

**URL:** https://www.greencity.cx.ua/#/greenCity/events

---

## TC-01: Check loading page

| Step | Action | Data | Expected Result |
|------|--------|------|-----------------|
| 1 | Open page | https://www.greencity.cx.ua/#/greenCity/events | Page succesfully opens, status 200 |
| 2 | Check the list of events | - | There are block of event cards |

## TC-02: Move to events details

| Step | Action | Data | Expected Result |
|------|--------|------|-----------------|
| 1 | Click on first card of events on button MORE | - | Page of events details opens |
| 2 | Check URL | - | URL contains `/event/` or something like that |

## TC-03: Filter by type

| Step | Action | Data | Expected Result |
|------|--------|------|-----------------|
| 1 | Select the "Eco-Lecture" filter | "Eco lecture" | The list of events is being updated |
| 2 | Check each event | - | All events are classified as "Eco-lectures" |



## TC-04: Find by no exists word

| Step | Action | Data | Expected Result |
|------|--------|------|-----------------|
| 1 | Push the button of searching | - | Opens the field of searching |
| 2 | Write in the field no exists words | yyyyyyyyy | The message "We didn't find any results matching to this search" appears |