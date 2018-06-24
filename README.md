# BGMPlayer
2015년 네터스 개인프로젝트

아직 미완성
APM SETUP이용

# 모티브
SKT 어플 뮤직메이트를 모티브로 제작하였고, 원래는 파싱을 추가하여 자동으로 인기 100곡이나 컨셉에 맞는 곡을 랜덤플레이 하는 기능으로 생각하였으나
시간이 부족하여 미완성된채 방치된 프로젝트...
나중에 수정할 예정

# DB 구조
-- phpMyAdmin SQL Dump
-- version 3.2.3
-- http://www.phpmyadmin.net
--
-- 호스트: localhost
-- 처리한 시간: 18-06-24 23:03 
-- 서버 버전: 5.1.41
-- PHP 버전: 5.2.12

SET SQL_MODE="NO_AUTO_VALUE_ON_ZERO";

--
-- 데이터베이스: `bean`
--

-- --------------------------------------------------------

--
-- 테이블 구조 `project`
--

CREATE TABLE IF NOT EXISTS `project` (
  `key` int(11) NOT NULL,
  `id` varchar(15) CHARACTER SET utf8 COLLATE utf8_unicode_ci NOT NULL,
  `name` varchar(30) CHARACTER SET euckr NOT NULL,
  PRIMARY KEY (`key`)
) ENGINE=MyISAM DEFAULT CHARSET=latin1;

--
-- 테이블의 덤프 데이터 `project`
--

INSERT INTO `project` (`key`, `id`, `name`) VALUES
(0, 'HCjNJDNzw8Y', 'Camila Cabello - Havana'),
(1, 'iCkYw3cRwLo', 'Youtube Stlye');
