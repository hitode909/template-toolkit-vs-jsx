Template Toolkit                        | JSX
----------------------------------------| ------------
`[% foo %]`                             |`{foo}`
`[% foo.bar %]`                         |`{foo.bar}`
`foo-[% bar %]`                         |<code>{\`foo-${bar}\`}</code>
`class="foo"`                           |`className="foo"`
`<label for="foo">`                     |`<label htmlFor="foo">`
`[% IF foo %]bar[% END %]`              |`{foo && 'bar'}`
`[% IF foo %]bar[% ELSE %]bazz[% END %]`|`{foo ? 'bar' : 'bazz'}`
