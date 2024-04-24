# css-notes
<h1>یکسری نکات و توضیحات برای css</h1>
<hr/>
<h3>_ بهترین روش gap و فاصله بین ستون ها بدون break شدن به خط بعدی</h3>

  ```
<style>
        body {
            overflow-x: hidden;
        }
    
        .amir {
            width: 50%;
        }

        .para {
            border: 1px solid blue;
        }

        .paramanfi {
            margin: -8px;
        }
    </style>
</head>

<body>
    <div class="w-100">
        <div class="d-flex flex-wrap paramanfi">
            <div class="amir p-2">
                <div class="para">
                    hiii
                </div>
            </div>
            <div class="amir p-2">
                <div class="para">
                    hiii
                </div>
            </div>
        </div>
    </div>
</body>
```

<p>به المان مورد نظر padding میدیم و به پرنتش ، مارجین منفی</p>
<hr/>
