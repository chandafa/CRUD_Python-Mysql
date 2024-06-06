# CRUD Python & Mysql

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)

## About <a name = "about"></a>

CRUD sederhana dengan python dan mysql berbasis CLI

## Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

### 1. menginstal modul mysql untuk Python

```
sudo apt install python-mysql.connector
```

### atau bisa juga menggunakan pip:

```
pip3 install mysql-connector
```

### 2. membuat database

```
python create_db.py
```

### 3. membuat table

```
python create_table.py
```

End with an example of getting some data out of the system or using it for a little demo.

## Usage <a name = "usage"></a>

Add notes about how to use the system.

### Insert Data

```
python insert_many.py

or

python insert_one.py

```

### Melihat data

```
python select_many.py

or

python select_one.py

```

### Update data

```
python update.py

```

### Hapus data

```
python delete.py

```

### Menjalankan aplikasi Full

```
python app_cruds.py

```
