# HTML

[Sample](sample.html)

## Formatting

* Indent with two spaces (not tabs)
* Prefer double quotes for HTML attributes
* Only add spacing line breaks between two nodes at the same indentation
  ```
    <div>
      <div>
        content
      </div>

      <div>
        more content
      </div>
    </div>
  ```  
* In-line elements such as spans should be written in-line
* Breaking elements such as divs should be broken
* Comments are always above the markup they reference
* However, comments should be avoided unless absolutely necessary
* Rows should generally not exceed 80 columns

## IDs and Classes

* Use meaningful names: `header` not `hdr`.
* Use ID and class names that are as short as possible but as long as necessary.
* IDs are always underscored, classes are always hyphenated
* Classes should be ordered from most general to most specific to the element they are describing
