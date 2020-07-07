# The First Project with GIT
 Das erste Projekt mit GIT

    if(newDialog->result() == QDialog::Accepted){
        rowPosition = this->ui->tableWidget->rowCount();
        this->ui->tableWidget->insertRow(rowPosition);
        Dialog_Main::ui->tableWidget->setItem(rowPosition,0,new QTableWidgetItem(newDialog->adresse_neu->Get_Anrede()));
        Dialog_Main::ui->tableWidget->setItem(rowPosition,1,new QTableWidgetItem(newDialog->adresse_neu->Get_Vorname()));
        Dialog_Main::ui->tableWidget->setItem(rowPosition,2,new QTableWidgetItem(newDialog->adresse_neu->Get_Nachname()));
        Dialog_Main::ui->tableWidget->setItem(rowPosition,3,new QTableWidgetItem(newDialog->adresse_neu->Get_Email()));
        Dialog_Main::ui->tableWidget->setItem(rowPosition,4,new QTableWidgetItem(newDialog->adresse_neu->Get_Geschlecht()));
        Dialog_Main::ui->tableWidget->setItem(rowPosition,5,new QTableWidgetItem(newDialog->adresse_neu->Get_GebDat()));
     if(you can see this)
     { all is good }
     else
     all is bad
