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


3/11/24:
* Starting to learn how to animate in order to show visually that you are doing that certain action (like punching or running). I decided to use Blender as in addition to animation I could also use it for modeling for the scenario on if I have to time beyond MVP to work on more cosmetic stuff. Here was the [video](https://www.youtube.com/watch?v=HDL__EYvP0U&t=525s) I had used in order to setup and learn on how to actually animate. What I learned so far is that animation use something called Keyframes and a collection of them turn into the bigger picture we see. 
