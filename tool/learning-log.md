# Tool Learning Log

Tool: **Roblox Lua**

Project: **Creating a Battlegrounds Game**

---

12/17/23:
* Learned how to use CFrame in order to rotate a part on its own
  ```lua
  local x = 0
  local part = script.Parent
  while true do
    part.CFrame = part.CFrame * CFrame.Angles(0, 0, math.rad(x))
    x = x + 1
    wait(0.02)
  end
  ```
* The problem is that it isn't a smooth rotation 


