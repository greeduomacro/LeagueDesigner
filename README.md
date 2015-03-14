# LeagueDesigner
LeagueDesigner is a  League of Legends website focused on enabling users to design their own League of Legends characters (known as "Champions"). The site will provide tools such as calculators and a way to collaborate with other users on the same project like github does.

# Features
1. Design and submit a Champion, which can be peer-rated and reviewed.
2. Calculators to aid in design, such as: per-level/at-maximum-level statistics, potential damage with items, %missing/%maximum damage, mitigated armor/magic resist/movement speed after damage/slows, crowd control reduction time after tenacity, etc.
3. Collaboration with other users on the same Champion.

# Pages

Every page will have a header with the Logo in the upper-left-hand corner, a search bar in the middle, and the user-login on the right-hand side.

Navbar buttons:
- Home
- Submit
- Browse
- About

### Home Page
- Jumbotron with a submit button and short blurb

### Submit page
The submit page will be based off of LoLKing's submit page.

1. [NAME], [TITLE] + accompanying splash art
2. Class tags: melee, assassin, pusher, etc.
3. Lore
4. Statistics
  - Health (+HP/lvl) | Maximum HP at 18
  - Mana (+Mana/lvl) | Maximum Mana at 18 | Selector for "alternative resource" which creates a text box to describe it
  - Mana Regen (+ManaRegen/lvl) | Maximum ManaRegen at 18
  - Attack Damage (+Attack Damage/lvl) | Maximum AD at 18
  - Attack Speed (+ASPD%/lvl) | Maximum ASPD at 18
  - Armor (+Armor/lvl) | Maximum armor at 18
  - Magic Resist (+Magic Resist/lvl) | Maximum Magic Resist at 18
  - Movement Speed
  - Attack Range
5. Outline of abilities
6. Explain role of Champion and playstyle
7. Additional comments

In addition, there will be a static div on the right side whose content changes based on what you have currently selected (for example, if you are currently inputting the Attack Damage stat, pull up Champion averages/mins/maxes of Attack Damage in the div).

### Browse page
- Sort submissions by different queries, such as highest rated, newest, oldest, lowest rated, etc. Default will be set to newest.

### View Page
The View page will be based off of LoLKing's view guide page.

- Contains all aspects of the submit page without editable properties and without the static div.
- Includes Rating button at the top next to title and a Comment section at the bottom.

### Login/Sign Up
- Simple two-column page with Login on the left and Sign Up on the right.
- Users Sign Up with their email address, preferred username, and password/confirm password.
- Users Login with their email address/username and password

### User Profile Page
- User Profile will have a picture (chosen from a selection of champion icons), in-game name, featured Champion design, a tab for submitted Champion designs, and a tab for favorited Champion designs.

### About page
- A general about page talking about our conquests and awesomeness, of course.
