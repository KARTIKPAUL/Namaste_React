1.Is JSX mandatory for React ?
Ans: No.

2.Is ES6 mandatory for React ?
Ans: No.

3.How can we write comments in JSX ?
Ans: <!-- Ans:  -->

4.What is <React.Fragment></React.Fragment> and <></> ?
Ans: In React, React.Fragment and it's shorthand syntax <></> are tools are used to group a list of children without adding extra nodes to the Document Object Model(DOM).

5.What is virtual DOM ?
Ans: The Virtual DOM(VDOM) is a programming concept where a "virtual" representation of a user interface(UI) is kept in memory and synced with the real DOM. This approach is most famously used by libraries likes React and Vue.

In simple terms,instead of changing the real browser DOM every time a state changes (which is slow), the library makes changes to a lightweight copy first.

6.What is Reconciliation in React ?
Ans: Reconciliation is the internal process React uses to update the browser's DOM efficiently.It's the "diffing" algorithm that determines which part of the UI need to be changes when a componenrt's state or props update.

7.What is React Fiber ?
Ans: React Fiber is the current reconciliation engine in React(introduced in version 16). It is a complete rewrite of the old reconciliation algorithm designed to increase it's suitability for areas like animation, layout and gestures.

8.Why we need keys in React? When do we need keys in React?
Ans: In React, keys help React Identity which items have changed, been added, or removed when rendering lists.They are essential for correct updates and good performances.

React uses a process called Reconciliation to update the UI efficiently. When a list changes, React compares the previous render with the next render.

9.Can we use index as a keys in React ?
Ans: Basically we not use index is a keys. But if there is no option then we need to use index as a keys.

10.What is the props in React ?
Ans: Props is similar to the argument in function we pass one component to another.

11.What is config driven UI ?
Ans: Config-Driven UI is a design pattern where the User Inerface is generated dynamically based on a "configuration"(uselly a JSON object) received from an API or a local File, rather than being hard-coded into the component logic.