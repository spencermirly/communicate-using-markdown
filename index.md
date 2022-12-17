# This is an h1 header
### This is an h3 header

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

```rust
 pub fn execute(&mut self, action: &ActionType){
        match action {
            ActionType::Run{prog, args} => self.run(prog, args),
            ActionType::Close => self.close(),
            ActionType::CycleFocus{direction} => self.cycle_focus(direction),
            ActionType::ChangeSize { amount } => self.change_size(amount),
            ActionType::NextScreen => self.next_screen(),
            ActionType::PromoteWindow => self.promote_window(),
            ActionType::MoveWindow => self.move_window(),
            ActionType::ToggleFull => self.toggle_full(),
            ActionType::Quit => self.quit()
        }
    }
```
- [ ] Finish CS471 Assignments
- [ ] Finish Sprint 4
- [ ] Finish Christmas Shopping
