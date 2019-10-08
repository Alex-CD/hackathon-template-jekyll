---

# Jekyll
layout: event

# Event info
name: "Sample Event 2"
location: "In a shed somewhere"

is-public: true # Makes this event visible in events list

start: "2099-01-01T12:00:00+00:00"
end: "2001-01-01T12:00:00+00:00"

short-description: "This is generated programatically"
display-date: ""

full-description: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum."

# Styling
color: "#800080"


# Jumbotron
display-logo: false
small-logo: "rh-small.svg"
logo-width: 1
jumbotron-image: ""
jumbotron-image-adjust: "rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)"


show-ticket-button: true
disable-button: true
tickets: "https://tickets.royalhackaway.com/"
ticket-button-text: "RSVP"

# Event page content

show-map: false
map-src: "https://maps.google.com/maps?q=windsor%20building%2C%20royal%20holloway%20university%20of%20london&t=&z=13&ie=UTF8&iwloc=&output=embed"

show-wifi-details: false
internet:
  ssid: ""
  username: ""
  password: ""


show-schedule: yes
schedule:
  "Saturday — Day 1":
    -
      - "10:00"
      - "Registration Opens"
    -
      - "11:00"
      - "Opening Ceremony"
    -
      - "12:00"
      - "Hacking Begins"
    -
      - "13:00"
      - "Lunch"
    -
      - "15:00"
      - "Using APIs (Workshop)"
    -
      - "16:00"
      - "Git and GitHub (Workshop)"
    -
      - "16:00"
      - "How to manage your team and win at hackathons (Workshop)"
    -
      - "18:00"
      - "Dinner"
    -
      - "21:00"
      - "MLH Minigame"
    -
      - "23:59"
      - "Midnight Pizza"
  "Sunday — Day 2":
    -
      - "08:00"
      - "Breakfast"
    -
      - "12:00"
      - "Hacking Ends w/ Lunch"
    -
      - "13:00"
      - "Presentations"
    -
      - "15:00"
      - "Judging"
    -
      - "16:00"
      - "Closing Ceremony"


show-sponsors-list: false
sponsors:
    -
      Name: "Example"
      Link: "https://www.example.com/"
      Icon: ""
      Colour: #A60000
    -
      Name: "Example2"
      Link: "https://www.example.com"
      Icon: ""
      Colour: #A60000

---


<section id="event-extra-content" style="background-color: {{ page.color }}">
  <div class="container text-light">
 <p class=""> this is some example extra content.</p>
</section>


This is some extra example content.
