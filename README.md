## Font Awesome CLI Tool

- So, what is this?

  It's a ruby script that prints out all the free font-awesome icons, and lets you fuzzy-find the one you want.


- How do I use it?

  Download `fa-icons`, put it somewhere in your $PATH, `chmod +x`, and type `fa-icons` in your terminal


- Dependencies?

  Oh, yeah, you need fzf (https://github.com/junegunn/fzf) and a terminal using a patched font (https://github.com/ryanoasis/nerd-fonts). I use kitty, but you can use whatever.


- Can I change the output format?
    
  Yeah, use the `--format` option with `html`, `slim`, or `rails`. You can also change the default on line 22.
    
    
- I want you to add another format!
    
  That's not a question, but you can go ahead an open a pull request with the format you want. 


- So what's it look like in action?

  https://youtu.be/2GszUY-8BEU
  
  
- What's the black text off to the right?

  Font Awesome made some search terms, and I left those in so fzf could use them. But that's pretty much it. It's not really important to look at them.
  
  
- Is it done?

  No. I've got a few more things I wanna add, but this is 90% there. 
