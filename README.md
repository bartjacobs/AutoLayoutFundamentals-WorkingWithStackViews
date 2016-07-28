### Auto Layout Fundamentals: Working With Stack Views

#### Author: Bart Jacobs

Auto Layout makes it easy to create layouts that look great on any device. But it is easy to lose sight of constraints when a layout gains in complexity. Apple realized this and made Auto Layout even more powerful with the addition of **stack views**.

The `UIStackView` class was introduced in iOS 9. By abstracting the task of creating and managing constraints, stack views helps developers create complex layouts with little effort. There are a few things you need to know about stack views before you can start using them in your layouts.

A stack view manages the position and size of the elements it contains. Even though `UIStackView` inherits from `UIView`, the stack view itself is not drawn to the screen. It behaves like a view, but it is invisible to the user. That is a definite advantage.

Another benefit of stack views is the ability to nest them. By nesting stack views, you can create complex layouts without being overwhelmed by dozens and dozens of constraints.

**Read this article on the [blog](https://cocoacasts.com/auto-layout-fundamentals-working-with-stack-views/)**.
