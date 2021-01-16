# Members

## Updating Members

The member list is found in `./_data/member_bios.yml`.

```yml
- name: Grant Batchelor
  initiation_number: 1
  linkedin_url: https://www.linkedin.com/in/grantbatchelor/
- name: Elliott Eskra
  initiation_number: 2
  linkedin_url: https://www.linkedin.com/in/elliott-eskra-2694348/
```

Adding new list entries to this file will cause them to automatically
appear in the member directory page.

## Rendering Member Information

`/_includes/member_table.html` is an HTML fragment that can be included with liquid
to display all members in a table. Update this fragment to include new metadata.
