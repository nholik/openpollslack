# Open source poll for slack

This repo is a fork of [GitLab](https://gitlab.com/KazuAlex/openpollslack) with some modifications for my particular needs.  Please visit that repo for updates and the original app.  Please visit the original creator and support if you find it useful.

## License

The code is under GNU GPL license. So, you are free to modify the code and redistribute it under same [license](LICENSE). 
  
Remember the four freedoms of the GPL :  
> the freedom to use the software for any purpose,
> * the freedom to change the software to suit your needs,
> * the freedom to share the software with your friends and neighbors, and
> * the freedom to share the changes you make.

## Command usages

### Simple poll
```
/poll "What's your favourite color ?" "Red" "Green" "Blue" "Yellow"
```
### Anonymous poll
```
/poll anonymous "What's your favourite color ?" "Red" "Green" "Blue" "Yellow"
```
### Limited choice poll
```
/poll limit 2 "What's your favourite color ?" "Red" "Green" "Blue" "Yellow"
```
### Hidden poll votes
```
/poll hidden "What's your favourite color ?" "Red" "Green" "Blue" "Yellow"
```
### Anonymous limited choice poll
```
/poll anonymous limit 2 "What's your favourite color ?" "Red" "Green" "Blue" "Yellow"
```
  
For both question and choices, feel free to use slack's emoji, `*bold*` `~strike~` `_italics_` and `` `code` ``  

