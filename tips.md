Use `UWPSpy` to discover styles

# Start menu
[src](https://ramensoftware.com/uwpspy#comment-15007)
Adjust the distance of the start menu from the left edge of the screen with:
`Target: StartDocked.StartSizingFrame`
`Style: Canvas.Left=100`
Replace 100 as needed.

# Taskbar
[src](https://ramensoftware.com/uwpspy#comment-15182)
(workaround) Target a taskbar button by its text content like this:
`Taskbar.TaskListButton[AutomationProperties.Name=UWPSpy - Ramen Software - Google Chrome - 1 running window]`
It’s not perfect, as the title can change. Also, the title is only matched when the taskbar button is created.
