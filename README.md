<div align="center">

## React query / Tanstack Query Infinite Scroll

</div>

First project created on the Udemy course [React Query: Server State Management in React](https://www.udemy.com/course/learn-react-query/?couponCode=REACT-QUERY-GITHUB)

### Learning summary:
* React Query manages
    * _pageParam_ for the next page to be fetched
    * _getNextPageParam_ option
    * could be from _lastPage_, or _allPages_
    * _hasNextPage_
        * boolean indicating wheter _pageParam_ is undefined
    * Component handles calling _fetchNextPage_
        * use _hasNextPage_ value to determine when to stop
