1.  I liked the website's color scheme and it has a nice navigation tab.
2.  I'd say my website is more maintainable because you're handicapping yourself a bit by having only one stylepage for the entire
    website.  while it is possible to do everything with one stylepage that can be done with multiple pages, it would be a lot harder to keep track things and reduce repetition as more detailed styles get added.
3.  The websites files are well organized, not sure if it matters but Turner.png is still capitalized.
4.  There was some duplication in the stylepage where you styled these elements by id individually where you could have given them a class and styled the class istead:
#dark-choco {
    width: 250px;
    height: 250px;
}

#white-choco {
    width: 250px;
    height: 250px;
}

#milk-choco {
    width: 250px;
    height: 250px;
}