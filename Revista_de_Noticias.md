- 👋 Hi, I’m @veri9669
- 👀 I’m interested in Database and web development :HTML5,CSS3,JAVASCRIPT... 
- 🌱 I’m currently learning  MYSQL,PHP,HTML5 ,CSS3
- 🏫I'm doing Faculdade Estacio in Fortaleza - ce and studying 2 Semester.
-💞️ I’m looking to collaborate on in Information Technology (IT) . 
- 📫 How to reach me ... 

<!---
veri9669/veri9669 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.>

---- MySQL Workbench Forward Engineering

SET @OLD_UNIQUE_CHECKS=@@UNIQUE_CHECKS, UNIQUE_CHECKS=0;
SET @OLD_FOREIGN_KEY_CHECKS=@@FOREIGN_KEY_CHECKS, FOREIGN_KEY_CHECKS=0;
SET @OLD_SQL_MODE=@@SQL_MODE, SQL_MODE='ONLY_FULL_GROUP_BY,STRICT_TRANS_TABLES,NO_ZERO_IN_DATE,NO_ZERO_DATE,ERROR_FOR_DIVISION_BY_ZERO,NO_ENGINE_SUBSTITUTION';

-- -----------------------------------------------------
-- Schema revista_noticias
-- -----------------------------------------------------

-- -----------------------------------------------------
-- Schema revista_noticias
-- -----------------------------------------------------
CREATE SCHEMA IF NOT EXISTS `revista_noticias` DEFAULT CHARACTER SET utf8 ;
USE `revista_noticias` ;

-- -----------------------------------------------------
-- Table `categorias`
-- -----------------------------------------------------
CREATE TABLE IF NOT EXISTS `categorias` (
  `id` INT(11) NOT NULL,
  `nome` VARCHAR(255) NOT NULL,
  PRIMARY KEY (`id`))
ENGINE = InnoDB
DEFAULT CHARACTER SET = utf8;


-- -----------------------------------------------------
-- Table `usuarios`
-- -----------------------------------------------------
CREATE TABLE IF NOT EXISTS `usuarios` (
  `id` INT(11) NOT NULL,
  `nome` VARCHAR(45) NULL DEFAULT NULL,
  `email` VARCHAR(255) NULL DEFAULT NULL,
  `senha` VARCHAR(255) NULL DEFAULT NULL,
  `tipo` INT(11) NULL DEFAULT NULL,
  `status` VARCHAR(255) NULL DEFAULT NULL,
  `Usuarioscol` VARCHAR(45) NULL DEFAULT NULL,
  PRIMARY KEY (`id`))
ENGINE = InnoDB
DEFAULT CHARACTER SET = utf8;


SET SQL_MODE=@OLD_SQL_MODE;
SET FOREIGN_KEY_CHECKS=@OLD_FOREIGN_KEY_CHECKS;
SET UNIQUE_CHECKS=@OLD_UNIQUE_CHECKS;

