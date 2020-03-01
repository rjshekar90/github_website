

git config --global user.name "Sam Smith" git config --global user.email sam@example.com


 1517  git init
 1518  ls
 1519  git config --global user.name "Raja Shekar"
 1520  ls
 1521  git config --global user.email rxs148130@utdallas.edu
 1522  git config --global user.email rjshekar90@gmail.com
 1523  git config --global user.email rxs148130@utdallas.edu
 1524  git config --global user.email "Raja Shekar" --replace-all
 1525  git config --global user.name "Raja Shekar" --replace-all
 1526  git config --global user.email rxs148130@utdallas.edu --replace-all
 1527  git user.name
 1528  git config user.name
 1529  git config user.email
 1530  echo contents > file1.py
 1531  echo contents2 > file2.py
 1532  ls -al
 1533  ls
 1534  git add .
 1535  git status
 1536  git rm --staged
 1537  git status
 1538  git commit -m "This is the first commit"
 1539  git status
 1540  git diff
 1541  git diff HEAD
 1542  git diff --staged
 1543  echo contents > file3.py
 1544  git status
 1545  git add ./
 1546  git status
 1547  echo contents.changes > file3.py
 1548  git status'
'
 1549  git status
 1550  git diff
 1551  git diff --staged
 1552  git diff HEAD
 1553  git commit -am "commited to Local repo"
 1554  git status
 1555  git diff
 1556  git diff --staged
 1557  git diff HEAD
 1558  git status
 1559  git log
 1560  ls
 1561  echo new contents added >> file1.py
 1562  git status
 1563  git commit -am "file1 modified"
 1564  git log
 1565  git log --oneline
 1566  git branch
 1567  echo "master version" >> *
 1568  echo "master version">>*
 1569  echo master version>>*
 1570  echo "master version" >> *
 1571  echo "master version" >>*
 1572  echo "master version" >> file1.py
 1573  echo "master version" >> file2.py
 1574  ls 
 1575  echo "master version" >> file3.py
 1576  echo "master version" >> 1.py
 1577  cat 1.py
 1578  ls
 1579  git status
 1580  git commit -am "master version"
 1581  git status
 1582  git log --oneline
 1583  git branch feature
 1584  git branch
 1585  git checkout feature
 1586  git branch
 1587  ls
 1588  git branch
 1589  echo "new file on feature" > file4.py
 1590  git status
 1591  echo "feature version" >> file1.py
 1592  echo "feature version" >> file2.py
 1593  echo "feature version" >> file3.py
 1594  git status
 1595  git commit -m "feature version"
 1596  git add .
 1597  git commit -m "feature version"
 1598  git checkout master
 1599  git branch
 1600  cat file2.py 
 1601  ls
 1602  git checkout feature 
 1603  ls
 1604  git checkout master
 1605  ls
 1606  echo "New content" > file5.py
 1607  ls
 1608  git status
 1609  git commit -am "adding file5.py"
 1610  git status
 1611  git add.
 1612  git add .
 1613  git commit -m "adding file5.py"
 1614  git status
 1615  git branch newbranch
 1616  git status
 1617  echo "update on file 5" > file5.py
 1618  cat file5.py 
 1619  git status
 1620  git add .
 1621  git commit -m "update on master"
 1622  ls
 1623  git staus
 1624  git statyus
 1625  git status
 1626  git log
 1627  git log --oneline
 1628  git branch
 1629  git checkout newbranch 
 1630  ls
 1631  echo "update on newbranch" > file5.py
 1632  git status
 1633  git add .
 1634  git status
 1635  git commit -m "update on newbranch"
 1636  ls
 1637  git log --oneline
 1638  git checkout master
 1639  git branch
 1640  git merge newbranch 
 1641  git status
 1642  cat file5.py 
 1643  echo "merged version" > file5.py 
 1644  git status
 1645  git add .
 1646  git commit -m "fixed conflicts"
 1647  git status
 1648  cat file5.py 
 1649  git merge newbranch
 1650  git branch
 1651  git checkout newbranch 
 1652  ls
 1653  cat file5.py 
 1654  git checkout master
 1655  git branch
 1656  git merge newbranch 
 1657  git branch -d newbranch 
 1658  git branch
 1659  ls
 1660  git clone https://github.com/<your github user id>/calc3.git
 1661  git clone https://github.com/rjshekar90/calc3.git
 1662  ls
 1663  git status
 1664  rm -rf calc3/
 1665  git status
 1666  cd ..
 1667  ls
 1668  git clone https://github.com/rjshekar90/calc3.git
 1669  ls
 1670  rm -rf calc3/
 1671  history
 1672  history > history_print.txt
