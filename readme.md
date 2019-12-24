gerar editor .config
root = true

[*]
end_of_line = lf
indent_style = space
indent_size = 2
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true

delete eslint original

yarn add eslint -D
yarn eslint --init

delete package-lock

yarn add prettier eslint-config-prettier eslint-plugin-prettier babel-eslint -D 

criar arquivo .prettierrc
{
"singleQuote": true,
"trailingComma": "es5"
}

                  
