Run the Script:

Execute the script with the following command:


```
python3 payload.py <path_to_vector_image> <path_to_payload_file> <path_to_output>
```
For example:

```
python3 payload.py example.jpg payload.php modified_example.jpg
```
This command will:

    Search for the magic number in example.jpg.
    Inject the contents of payload.php into the file at the location right after the magic number.
    Save the modified file as modified_example.jpg.