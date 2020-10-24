# Contributing to Awesome Shields
+ The main idea is to add some more style to the shields, while keeping them informative.
+ We do not hardcode the output of the right part, just the color (if needed).
+ Shield source should start with *img.shields.io*.
+ We can specify *alt* and *source*, but not the *href*.

# Example of proper addition
<table>
      <tr>
        <td>Bitrise</td>
        <td>
            <a href="https://shields.io/category/build">
              <img
               src="https://img.shields.io/bitbucket/pipelines/atlassian/adf-builder-javascript/task/SECO-2168?branch=master&label=Bitrise&logo=Bitrise&logoColor=ffffff&labelColor=282828"
               alt="Bitrise Dark"
              >
            </a>
            <a href="https://shields.io/category/build">
              <img
               src="https://img.shields.io/bitbucket/pipelines/atlassian/adf-builder-javascript/task/SECO-2168?branch=master&label=Bitrise&logo=Bitrise&logoColor=ffffff&labelColor=683D87"
               alt="Bitrise Service Theme"
              >
            </a>
        </td>
    </tr>
</table>

```
    <tr>
        <td>Bitrise</td>
        <td>
            <a href="https://shields.io/category/build">
              <img
               src="https://img.shields.io/bitbucket/pipelines/atlassian/adf-builder-javascript/task/SECO-2168?branch=master&label=Bitrise&logo=Bitrise&logoColor=ffffff&labelColor=282828"
               alt="Bitrise Dark"
              >
            </a>
            <a href="https://shields.io/category/build">
              <img
               src="https://img.shields.io/bitbucket/pipelines/atlassian/adf-builder-javascript/task/SECO-2168?branch=master&label=Bitrise&logo=Bitrise&logoColor=ffffff&labelColor=683D87"
               alt="Bitrise Service Theme"
              >
            </a>
        </td>
    </tr>
```

**Contribution guidelines are "young", because the project has just started, therefore there might be some changes in the future.**
