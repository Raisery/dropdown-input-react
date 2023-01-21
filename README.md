# React Dropdown Input

This is a simple react component for a dropdown menu.


![](https://github.com/Raisery/dropdown-input-react/blob/main/assets/dropdown-close.png?raw=true)

![](https://github.com/Raisery/dropdown-input-react/blob/main/assets/dropdown-open.png?raw=true)


# Installation


The package can be installed via [npm]:

```
npm i dropdown-input-react
```

## Configuration

You can use the Dropdown with:

```js
const Example = () => {
  const [dropdownValue, setDropDownValue] = useState(new Date());
  return (
    <Dropdown className="exemple-class" inputId="exemple-id" data={['option1','option2', 'option3']} onChange={(event) => setDropDownValue(event.target.value)} />
  );
};
```
inputId is the id of the input in the Dropdown element, dont forget to use it if you need to link the input with a label.
data is an array of strings of all options.
