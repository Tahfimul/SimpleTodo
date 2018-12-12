# Pre-work - SMTWTFS

**SMTWTFS** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: **Tahfimul Latif**

Time spent: **2** hours spent in total

## User Stories

The following **required** functionality is completed:

* [X] User can **successfully add and remove items** from the todo list
* [X] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [X] User can **persist todo items** and retrieve them properly on app restart

The following **optional** features are implemented:

* [ ] Persist the todo items [into SQLite](http://guides.codepath.com/android/Persisting-Data-to-the-Device#sqlite) instead of a text file
* [ ] Improve style of the todo items in the list [using a custom adapter](http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView)
* [ ] Add support for completion due dates for todo items (and display within listview item)
* [ ] Use a [DialogFragment](http://guides.codepath.com/android/Using-DialogFragment) instead of new Activity for editing items
* [ ] Add support for selecting the priority of each todo item (and display in listview item)
* [ ] Tweak the style improving the UI / UX, play with colors, images or backgrounds

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://media.giphy.com/media/1ioigmMCQZO8w8I8Sp/giphy.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Giphy](https://www.giphy.com/).

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1:** "What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used."

**Answer:** I appreciate the structure of the Android framework using Java as its lanugage for Android App Development. In the past, I have done web development which was not as pleasant an

experience as is Android App Development due to the way HTML and JS are structured.

**Question 2:** "Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android? Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`."

**Answer:** Adapter is a class in Android that can be thought of as a container that sits between List View and the layout. It takes input data and 
adapts it to the layout. It is important because without this special class, it would be difficult for developers to adapt their data to a listView and
display it to the users.

getView() method is an important method because it parses critical data for each of the views as they are pu=opulated 
in the listView. convertView is responsible to removing old views as user scrolls through the listView.
## Notes

Describe any challenges encountered while building the app.

While I am knowledgeable about both the Android Framework and Java, I lack some knowledge that is required to make this app work
I did not have enough experience working with listView and Adapters. This actvity allowed me some exposure to also save and
retrieve data from system using the commons library and overall helped me get a better grip on polymorphism.

## License

    Copyright [2018] [Tahfimul Latif]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
