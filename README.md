

# flashy-tableviews

Let's play with a few more CocoaPods that I think are pretty great.

## Instructions

  1. Create a new Project and add [SWTableViewCell](https://github.com/CEWendel/SWTableViewCell) and [ARParallaxHeader](https://github.com/apping/APParallaxHeader) Pods to it.
  2. Drop in a `UITableViewCell` and implement both the parallax header (like twitter!) and the swipeable cells. Read documentation, play with the example app, etc.

## Advanced

  1. The cell returns the button presses using a delegate. Add `<SWTableViewCellDelegate>` in the header declaration and implement this method `(void)swipeableTableViewCell:(SWTableViewCell *)cell didTriggerRightUtilityButtonWithIndex:(NSInteger)index;`.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/flashy-tableviews' title='flashy-tableviews'>flashy-tableviews</a> on Learn.co and start learning to code for free.</p>
