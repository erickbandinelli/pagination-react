#### I am using the following technologies - Read the Documentation

-   [ES6](http://es6-features.org/) Obs: Read the Documentation
-   [styled-components](https://www.styled-components.com/) Obs: Read the Documentation

## Copy and paste the code below.

```
	const [currentPage, setCurrentPage] = useState(1);
	const [listPerPage] = useState(4);

	const paginate = (pageNumber) => setState(pageNumber);
	const indexOfLastList = currentPage * listPerPage;
	const indexOfFirstList = indexOfLastList - listPerPage;

	const currentlist = yourState.slice(indexOfFirstList, indexOfLastList);
```


## Copy and paste the code below.

```
	<Pagination
		currentPage={currentPage}
		listPerPage={listPerPage}
		totalList={yourState.length}
		paginate={paginate} />
```
