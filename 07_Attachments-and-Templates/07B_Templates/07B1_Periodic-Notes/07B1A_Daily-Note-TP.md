---
tags                         : #templates/periodic-notes/daily-note
previous_night_sleep_hrs     : 
previous_night_sleep_quality : 
todays_memories              : 
todays_learnings             : 
day_accomplishements         :
day_obstacles                :
day_events                   : ![[<%tp.date.now("YYYY-MM-DD")%>### Day log]]
day_rating                   :
day_energy_physical          : 
day_energy_mental            : 
day_energy_emotional         :
noon_sleep_taken             :
noon_sleep_hrs               :
noon_sleep_quality           :
energy_reasons               :
todays_location_log          :
---

# Greetings Rohan!

<<  [[<% tp.date.yesterday () %>]]  |  [[<% tp.date.tomorrow () %>]]   >>

---

## On this day 

[[<% tp.date.now("YYYY-MM-DD", "P-1Y") %>]]

## Reminders 

### Today's Focus 

> Start writing xyz

### Some important Links

> [[01C1A_My-Daily-Reminders]]
> [[01C1B_My-Not-to-do-list]]

![[<%tp.date.now("YYYY-MM-DD", -1)%>## Improvements]] 

---

## Today's Three

> Three tasks outside of dailies that would complete the day. 

```
- [ ] Replace me
- [ ] Replace me
- [ ] Replace me
```

<%* if (tp.date.now("ddd") == "Sun") { %>
- [ ] Make Weekly Note
<%*} %> 
<%* if (tp.date.now("D") == "1") { %>
- [ ] Make Monthly Note
<%*} %> 
<%* if (tp.date.now("M-D") == "1-1") { %>
- [ ] Make Yearly Note
<%*} %> 

---

## Journals 

### Gratitude Journal 

* I am grateful for 
* I am grateful for 

### Prompts 

> Choose a few questions from [[01C1C_Prompts]] to answer. 

---

## Logs 

### Files Created 

> These are the files i have created today. 

```query
line:(Created :: <%tp.date.now("YYYY-MM-DD")%>)
```

### Content Consumed

> Link all the notes which links to content consumption. 


### Day log 

> Link your notes having your thoughts, events etc. that are related to  : <%tp.date.now("YYYY-MM-DD")%>



#### Personal-Log

> Write about all that's personal

#### Work-Log

> Academics, projects go in here. 



---

## Schedule

### Morning

<%tp.file.include("[[07B1B_Routines-Morning]]")%>

### Noon

<%tp.file.include("[[07B1C_Routines-Noon]]")%>

### Evening / Night

<%tp.file.include("[[07B1D_Routine-Evening-Night]]")%>


---

## Improvements 

> Notes for my future self for improving. 



> Previous day improvement effectiveness notes. 



