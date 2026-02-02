# effective-engine
pip install textualFeatures Tasks: add / list / complete (with priority + due date) Notes: quick capture + search Habits: define habits + daily check-ins Log: mood + energy + focus (daily) Weekly report: auto-generates a summary Export: creates a Markdown report you can post/share Local-first = no  Tasks: add / list / complete (with priority + du.
server, no accounts, no bullshit.Features┌──────────────────────────────┐
│ ATLAS_OS — TODAY            │
├──────────────────────────────┤
│ Top 3 Tasks                 │
│ ▢ Ship Gumroad product      │
│ ▢ Post LinkedIn             │
│ ▢ Design page 4             │
│                             
│ Habits:  3/5 done           │
│ Mood: 7  Energy: 6  Focus: 5│
│                             
│ Commands: [a] add [d] done  │
└──────────────────────────────┘
atlas focus 25
🔥 Focus streak: 6 days
atlas weekly-export --pdf
rich.liverich.tablefrom rich.live import Live
from rich.table import Table
from time import sleep

def render():
    table = Table(title="ATLAS OS — TODAY")
    table.add_column("Task")
    table.add_row("Ship product")
    table.add_row("Workout")
    table.add_row("Design page")

    return table

def dashboard():
    with Live(render(), refresh_per_second=1) as live:
        while True:
            sleep(1)
python dashboard.py
gh repo clone aaxhixh1-a11y/effective-engine


            
